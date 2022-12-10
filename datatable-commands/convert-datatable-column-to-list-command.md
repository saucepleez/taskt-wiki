<!--TITLE: Convert DataTable Column To List Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Convert Column &gt; Convert DataTable Column To List


# Convert DataTable Column To List Command


## What does this command do?
This command allows you to convert DataTable Column to List


## When would I want to use this command?
Use this command when you want to convert DataTable Column to List.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please specify Column type](#param_1)
- [Please enter the Name or Index of the Column](#param_2)
- [Please Specify the Variable Name To Assign The List](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable to fet rows from.</dd>
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
### Please enter the Name or Index of the Column


<dl>
<dt>What to input</dt><dd>Enter a valid Column index value</dd>
<dt>Sample Data</dt><dd>id or 0 or {vColumn} or -1</dd>
<dt>Remarks</dt><dd>If -1 is specified for Column Index, it means the last column.</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Variable Name To Assign The List


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertDataTableColumnToListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
