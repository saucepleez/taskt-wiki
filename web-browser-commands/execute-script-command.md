<!--TITLE: Execute Script Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Execute Script


# Execute Script Command


## What does this command do?
This command allows you to execute a script in a Selenium web browser session.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Enter the instance name (ex. myInstance, {{vInstance})](#param_0)
- [Optional - Please Specify script code type (Default is Code)](#param_1)
- [Please Enter the script code](#param_2)
- [Optional - Please Enter the timeout in seconds (Default is 0)](#param_3)
- [Optional - Please Specify the Supply Argument](#param_4)
- [Optional - Please select the variable to receive the data](#param_5)
- [Please Specify the Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstance, {{vInstance})


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify script code type (Default is Code)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Code</strong> or  <strong>File</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Enter the script code


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If selected Code plese enter script code.
If selected File, please enter script file path.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Enter the timeout in seconds (Default is 0)


<dl>
<dt>What to input</dt><dd>If less than or equal to 0, wait for the script to finish.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>time &gt;= 1 is async, time &lt;= 0 is sync<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Supply Argument


<dl>
<dt>What to input</dt><dd>The value of the argument can be obtained with 'arguments[0]' in code.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please select the variable to receive the data


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserExecuteScriptCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
