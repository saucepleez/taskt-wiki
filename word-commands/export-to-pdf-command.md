<!--TITLE: Export To PDF Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Word Commands &gt; Export To PDF


# Export To PDF Command


## What does this command do?
This command allows you to export a Word document to a PDF.


## When would I want to use this command?
Use this command when you want to save a document to a PDF.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please indicate the path of the new pdf](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Word command</dd>
<dt>Sample Data</dt><dd>myInstance or wordInstance</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Word command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please indicate the path of the new pdf


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.pdf or {vWordPDFFilePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WordExportToPDFCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
