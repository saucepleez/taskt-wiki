<!--TITLE: Move Shape By Name Command -->
<!-- SUBTITLE: a command in the Excel group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel &gt; Shape &gt; Move Shape By Name


# Move Shape By Name Command


## What does this command do?
This command allows you to move Shape by Name


## When would I want to use this command?
Use this command when you want to move Shape by Name


<a id="param_list"></a>
## Command Parameters
- [Please Select the Excel Instance Name](#param_0)
- [Please Specify the Shape Name](#param_1)
- [Optional - Please Select the X Position](#param_2)
- [Optional - Please Select the Y Position](#param_3)
- [Optional - Please Select the When Fail Action](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Select the Excel Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel Instance Name</dd>
<dt>Value</dt><dd>Excel Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>RPAExcel or {vInstance}</dd>
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
### Please Specify the Shape Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>Rectangle 1 or {vShape}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Rectangle 1</strong> | Specify **Rectangle 1** for Shape Name |
| <strong>{vShape}</strong> | Specify Variable Name **vShape** for Shape Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the X Position


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Current X Position</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Y Position


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Current Y Position</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the When Fail Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing To Do |
| <strong>Error</strong> | Rise an Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelMoveShapeByNameCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
