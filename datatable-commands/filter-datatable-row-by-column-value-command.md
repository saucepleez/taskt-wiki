<!--TITLE: Filter DataTable Row By Column Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; DataTable Action &gt; Filter DataTable Row By Column Value


# Filter DataTable Row By Column Value Command


## What does this command do?
This command allows you to Filter Rows by reference to Column values.


## When would I want to use this command?
Use this command when you want to Filter Rows by reference to Column values.


## Command Parameters
- [Please select a DataTable Variable Name to Filter](#param_0)
- [Optional - Please specify Column type](#param_1)
- [Please enter the Name or Index of the Column](#param_2)
- [Please select filter target value type](#param_3)
- [Please select filter action](#param_4)
- [Additional Parameters](#param_5)
- [Please select a DataTable Variable Name of the Filtered DataTable](#param_6)
- [Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please select a DataTable Variable Name to Filter


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vTable or {vTable}</dd>
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
### Please select filter target value type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Text or Number</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please select filter action


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Additional Parameters


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Please select a DataTable Variable Name of the Filtered DataTable


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vNewTable or {vNewTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: FilterDataTableRowByColumnValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
