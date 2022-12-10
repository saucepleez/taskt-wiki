<!--TITLE: Format Data Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Data Commands &gt; Format Data


# Format Data Command


## What does this command do?
This command allows you to apply formatting to a string


## When would I want to use this command?
Use this command when you want to apply specific formatting to text or a variable


## Command Parameters
- [Please supply the value or variable.](#param_0)
- [Please select the type of data](#param_1)
- [Specify required output format](#param_2)
- [Please select the variable to receive output](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please supply the value or variable.


<dl>
<dt>What to input</dt><dd>Specify either text or a variable that contains a date or number requiring formatting</dd>
<dt>Sample Data</dt><dd>{DateTime.Now} or 1/1/2000 or 2500 or {vNum} or C:\temp\myfile.txt</dd>
<dt>Remarks</dt><dd>You can use known text or variables.</dd>
</dl>




<a id="param_1"></a>
### Please select the type of data


<dl>
<dt>What to input</dt><dd>Indicate the source type</dd>
<dt>Sample Data</dt><dd>Choose Date or Number or Path</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Specify required output format


<dl>
<dt>What to input</dt><dd>Specify if a specific string format is required.</dd>
<dt>Sample Data</dt><dd>MM/dd/yy or hh:mm or #.0 or file etc.</dd>
<dt>Remarks</dt><dd>Path supports file, folder, filewithoutextension, extension, drive</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive output


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable or {vSomeVariable}</dd>
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
Automation Class Name: FormatDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
