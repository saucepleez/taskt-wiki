<!--TITLE: Add DataTable Rows By DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Row Action &gt; Add DataTable Rows By DataTable


# Add DataTable Rows By DataTable Command


## What does this command do?
This command allows you to add a DataTable Row to a DataTable by a DataTable


## When would I want to use this command?
Use this command when you want to add a DataTable Row to a DataTable by a DataTable.


<a id="param_list"></a>
## Command Parameters
- [Please Select the DataTable Variable Name to be added a row](#param_0)
- [Please Select the DataTable Variable Name to add to the DataTable](#param_1)
- [Optional - Please Select the When DataTable (to add) Column does not Exists](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the DataTable Variable Name to be added a row


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vDataTable or {vDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDataTable</strong> | Specify Variable Name **vDataTable** |
| <strong>{vDataTable}</strong> | Specify Variable Name **vDataTable** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the DataTable Variable Name to add to the DataTable


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vDataTable or {vDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDataTable</strong> | Specify Variable Name **vDataTable** |
| <strong>{vDataTable}</strong> | Specify Variable Name **vDataTable** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the When DataTable (to add) Column does not Exists


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Do not add a Column |
| <strong>Error</strong> | Rise a Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: AddDataTableRowsByDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
