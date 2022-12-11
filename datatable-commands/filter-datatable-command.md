<!--TITLE: Filter DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Other &gt; Filter DataTable


# Filter DataTable Command


## What does this command do?
This command allows you filter a DataTable into a new Datatable


## When would I want to use this command?
Use this command when you want to get specific rows of a DataTable.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Please indicate the output DataTable Variable Name](#param_1)
- [Please indicate tuples to filter by.](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter the DataTable name you would like to filter through.</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Sample Data</dt><dd><strong>myDataTable</strong> or <strong>{vMyDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the output DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a unique DataTable name for future reference.</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Sample Data</dt><dd><strong>newData</strong> or <strong>{vNewData}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please indicate tuples to filter by.


<dl>
<dt>What to input</dt><dd>Enter a tuple containing the column name and item you would like to filter by.</dd>
<dt>Sample Data</dt><dd>{ColumnName1,Item1},{ColumnName2,Item2}</dd>
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
Automation Class Name: FilterDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
