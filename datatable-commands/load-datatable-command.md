<!--TITLE: Load DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; DataTable Action &gt; Load DataTable


# Load DataTable Command


## What does this command do?
This command gets a range of cells and applies them against a dataset


## When would I want to use this command?
Use this command when you want to quickly iterate over Excel as a dataset.


## Command Parameters
- [Please create a DataTable Variable Name](#param_0)
- [Please indicate the workbook file path](#param_1)
- [Please indicate the sheet name](#param_2)
- [Indicate if Header Row Exists](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please create a DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Indicate a unique reference name for later use</dd>
<dt>Sample Data</dt><dd>vMyDataset or {vMyDataset}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the workbook file path


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the workbook file</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.xlsx or {vFilePath}</dd>
<dt>Remarks</dt><dd>This command does not require Excel to be opened.  A snapshot will be taken of the workbook as it exists at the time this command runs.</dd>
</dl>




<a id="param_2"></a>
### Please indicate the sheet name


<dl>
<dt>What to input</dt><dd>Indicate the specific sheet that should be retrieved.</dd>
<dt>Sample Data</dt><dd>Sheet1 or mySheet or {vSheet}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Indicate if Header Row Exists


<dl>
<dt>What to input</dt><dd>Select the necessary indicator</dd>
<dt>Sample Data</dt><dd>Select Yes, No.  Data will be loaded as column headers if YES is selected.</dd>
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
Automation Class Name: LoadDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
