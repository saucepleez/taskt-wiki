<!--TITLE: Delete DataTable Column Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Column Action &gt; Delete DataTable Column


# Delete DataTable Column Command


## What does this command do?
This command allows you to delete a column to a DataTable


## When would I want to use this command?
Use this command when you want to delete a column to a DataTable.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please specify the Column type](#param_1)
- [Please specify the Column Name to delete](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable to add rows to.</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Column type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Column Name or Index</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Column Name</dd>
</dl>




<a id="param_2"></a>
### Please specify the Column Name to delete


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or newColumn or {vColumn} or -1</dd>
<dt>Remarks</dt><dd>If -1 is specified for Column Index, it means the last column.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: DeleteDataTableColumnCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
