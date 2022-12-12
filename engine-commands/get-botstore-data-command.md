<!--TITLE: Get BotStore Data Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Engine Commands &gt; Get BotStore Data


# Get BotStore Data Command


## What does this command do?
This command allows you to get data from tasktServer.


## When would I want to use this command?
Use this command when you want to retrieve data from tasktServer


## Command Parameters
- [Please Specify the Please indicate a name of the key to retrieve](#param_0)
- [Please Select the Indicate whether to retrieve the whole record or just the value](#param_1)
- [Please Specify the Select the variable to receive the output](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Specify the Please indicate a name of the key to retrieve


<dl>
<dt>What to input</dt><dd>Select a variable or provide an input value</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select the Indicate whether to retrieve the whole record or just the value


<dl>
<dt>What to input</dt><dd>Depending upon the option selected, the whole record with metadata may be required.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Retrieve Value</strong> or  <strong>Retrieve Entire Record</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Select the variable to receive the output


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
