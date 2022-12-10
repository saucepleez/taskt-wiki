<!--TITLE: Delete Cell Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Cell &gt; Delete Cell


# Delete Cell Command


## What does this command do?
This command allows you to delete a specified cell in Excel


## When would I want to use this command?
Use this command when you want to delete a specific cell from the current sheet.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Indicate the range to delete ex. A1 or A1:C1](#param_1)
- [Should the cells below shift upward after deletion?](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or excelInstance</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Indicate the range to delete ex. A1 or A1:C1


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>A1, B10, {vAddress}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Should the cells below shift upward after deletion?


<dl>
<dt>What to input</dt><dd>Indicate whether the row below will be shifted up to replace the old row.</dd>
<dt>Sample Data</dt><dd>Select 'Yes' or 'No'</dd>
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
Automation Class Name: ExcelDeleteCellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
