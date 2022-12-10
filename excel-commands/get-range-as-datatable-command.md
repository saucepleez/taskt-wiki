<!--TITLE: Get Range As Datatable Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Range &gt; Get Range As Datatable


# Get Range As Datatable Command


## What does this command do?
This command gets text from a specified Excel Range and put it into a DataTable.


## When would I want to use this command?
Use this command when you want to get a value from a specific range.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the First Cell Location (ex. A1 or B2)](#param_1)
- [Please select output Option](#param_2)
- [Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)](#param_3)
- [Add Headers](#param_4)
- [Assign to Variable](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or excelInstance</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the First Cell Location (ex. A1 or B2)


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>A1, B10, {vAddress}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select output Option


<dl>
<dt>What to input</dt><dd>Indicate whether this command should return a datatable or Delimited String</dd>
<dt>Sample Data</dt><dd>Select from Datatable or Delimited String</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>A1, B10, {vAddress}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Add Headers


<dl>
<dt>What to input</dt><dd>When selected, the column headers from the specified spreadsheet range are also extracted.</dd>
<dt>Sample Data</dt><dd>Select from Yes or No</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Assign to Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelGetRangeCommandAsDT
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
