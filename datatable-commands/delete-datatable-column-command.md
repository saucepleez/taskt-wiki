<!--TITLE: Delete DataTable Column Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Column Action &gt; Delete DataTable Column


# Delete DataTable Column Command


## What does this command do?
This command allows you to delete a column to a DataTable


## When would I want to use this command?
Use this command when you want to delete a column to a DataTable.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please specify the Column type](#param_1)
- [Please specify the Column Name to delete](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable to add rows to.</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>myDataTable</strong> or <strong>{vMyDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please specify the Column type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Column Name</strong> or  <strong>Index</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Column Name</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please specify the Column Name to delete


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>newColumn</strong> or <strong>{vColumn}</strong> or <strong>-1</strong></dd>
<dt>Remarks</dt><dd>If <strong>-1</strong> is specified for Column Index, it means the last column.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: DeleteDataTableColumnCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
