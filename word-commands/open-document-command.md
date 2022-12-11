<!--TITLE: Open Document Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Word Commands &gt; Open Document


# Open Document Command


## What does this command do?
This command opens an Word Document.


## When would I want to use this command?
Use this command when you want to open an existing Word Document.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please indicate the workbook file path](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Word</strong> command</dd>
<dt>Instance Type</dt><dd>Word</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>wordInstance</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Word</strong> command will cause an error.</dd>
</dl>




<a id="param_1"></a>
### Please indicate the workbook file path


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file that should be opened by Excel.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.docx or {vFilePath}</dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement extentions supported by Word.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WordOpenDocumentCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
