<!--TITLE: Convert JSON To List Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Convert &gt; Convert JSON To List


# Convert JSON To List Command


## What does this command do?
This command allows you to convert JSON Array into a List.


## When would I want to use this command?
Use this command when you want to convert JSON Array into a List


## Command Parameters
- [Please Select the Supply the JSON Array or Variable](#param_0)
- [Please select the variable to receive the List](#param_1)
- [Please Specify the Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Select the Supply the JSON Array or Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable or json array value</dd>
<dt>Instance Type</dt><dd>JSON</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>[1,2,3]</strong> or <strong>[{obj1},{obj2}]</strong> or <strong>{vArrayVariable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the variable to receive the List


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertJSONToListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
