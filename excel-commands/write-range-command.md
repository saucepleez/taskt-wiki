<!--TITLE: Write Range Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Range &gt; Write Range


# Write Range Command


## What does this command do?
This command writes a datatable to an excel sheet starting from the given cell address.


## When would I want to use this command?
Use this command when you want to set a value to a specific cell.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the Datatable Variable Name to Set](#param_1)
- [Please Enter the Cell Location to start from (ex. A1 or B2)](#param_2)
- [Add Headers](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or excelInstance</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the Datatable Variable Name to Set


<dl>
<dt>What to input</dt><dd>Enter the text value that will be set.</dd>
<dt>Sample Data</dt><dd>Hello World or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Enter the Cell Location to start from (ex. A1 or B2)


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>A1, B10, {vAddress}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Add Headers


<dl>
<dt>What to input</dt><dd>When selected, the column headers from the specified spreadsheet range are also written.</dd>
<dt>Sample Data</dt><dd>Select from Yes or No</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelWriteRangeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
