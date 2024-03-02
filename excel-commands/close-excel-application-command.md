<!--TITLE: Close Excel Application Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Instance &gt; Close Excel Application


# Close Excel Application Command


## What does this command do?
This command allows you to close Excel.


## When would I want to use this command?
Use this command when you want to close an open instance of Excel.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Excel Instance Name](#param_0)
- [Optional - Please Select the If the Workbook should be Saved](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the Excel Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel Instance Name</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>RPAExcel</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Please specify the Excel Instance Name created by <strong>Create Excel Instance</strong> command in advance.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPAExcel</strong> | Specify **RPAExcel** for Excel Instance Name |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for Excel Instance Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the If the Workbook should be Saved


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>True</strong> or  <strong>False</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>False</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>True</strong> | If the Workbook needs to be Saved, Save it and then Close it |
| <strong>False</strong> | Whether the Workbook needs to be Saved or not, Close it without saving |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelCloseApplicationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/16/23 05:54 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
