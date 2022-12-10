<!--TITLE: Add Workbook Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; File/Book &gt; Add Workbook


# Add Workbook Command


## What does this command do?
This command adds a new Excel Workbook.


## When would I want to use this command?
Use this command when you want to add a new workbook to an Exel Instance


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Optional - Please Select If Workbook Exists](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Select If Workbook Exists


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Error or Add</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Error</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelAddWorkbookCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
