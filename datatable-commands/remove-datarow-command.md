<!--TITLE: Remove DataRow Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Other &gt; Remove DataRow


# Remove DataRow Command


## What does this command do?
This command allows you remove specified data rows.


## When would I want to use this command?
Use this command when you want to delete a specific row.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Please indicate tuples to delete column rows](#param_1)
- [Please select overwrite option](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter the name of your DataTable</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate tuples to delete column rows


<dl>
<dt>What to input</dt><dd>Enter a tuple containing the column name and item you would like to remove.</dd>
<dt>Sample Data</dt><dd>{ColumnName1,Item1},{ColumnName2,Item2}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select overwrite option


<dl>
<dt>What to input</dt><dd>Indicate whether this command should remove rows with all the constraints or remove them with 1 or more constraints</dd>
<dt>Sample Data</dt><dd>Select from And or Or</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RemoveDataRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
