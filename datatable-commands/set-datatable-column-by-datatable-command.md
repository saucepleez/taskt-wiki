<!--TITLE: Set DataTable Column By DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Column Action &gt; Set DataTable Column By DataTable


# Set DataTable Column By DataTable Command


## What does this command do?
This command allows you to set a column to a DataTable by a DataTable


## When would I want to use this command?
Use this command when you want to set a column to a DataTable by a DataTable.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please specify Column type](#param_1)
- [Please specify the Column Name to set](#param_2)
- [Please specify the DataTable to set new Column values](#param_3)
- [Optional - If the number of rows is less than the DataTable to set](#param_4)
- [Optional - If the number of DataTable items is less than the rows to setted DataTable](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable to add rows to.</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify Column type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Column Name or Index</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Column Name</dd>
</dl>




<a id="param_2"></a>
### Please specify the Column Name to set


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or newColumn or {vNewColumn} or -1</dd>
<dt>Remarks</dt><dd>If -1 is specified for Column Index, it means the last column.</dd>
</dl>




<a id="param_3"></a>
### Please specify the DataTable to set new Column values


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vDataTable or {vDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Optional - If the number of rows is less than the DataTable to set


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Add Rows or Error</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_5"></a>
### Optional - If the number of DataTable items is less than the rows to setted DataTable


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Error</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetDataTableColumnValuesByDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
