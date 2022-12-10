<!--TITLE: Open Workbook Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; File/Book &gt; Open Workbook


# Open Workbook Command


## What does this command do?
This command opens an Excel Workbook.


## When would I want to use this command?
Use this command when you want to open an existing Excel Workbook.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please indicate the workbook file path](#param_1)
- [Optional - Please indicate open password](#param_2)
- [Optional - Please Specify If Worksheet Exists](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error.</dd>
</dl>




<a id="param_1"></a>
### Please indicate the workbook file path


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file that should be opened by Excel.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.xlsx or {vFilePath}</dd>
<dt>Remarks</dt><dd>If file does not contain extension, supplement extensions supported by Excel.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_2"></a>
### Optional - Please indicate open password


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file that should be opened by Excel.</dd>
<dt>Sample Data</dt><dd>myPassword or {vPassword}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Please Specify If Worksheet Exists


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Error or Ignore or Open</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Error</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelOpenWorkbookCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
