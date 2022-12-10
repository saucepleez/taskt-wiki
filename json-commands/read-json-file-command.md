<!--TITLE: Read JSON File Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
JSON Commands &gt; File &gt; Read JSON File


# Read JSON File Command


## What does this command do?
This command reads JSON data into a variable


## When would I want to use this command?
Use this command when you want to read data from JSON files.


## Command Parameters
- [Please indicate the path to the file](#param_0)
- [Please define where the JSON should be stored](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please indicate the path to the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the text file.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.txt or {vTextFilePath} or http://example.com/api/ or {vURL}</dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement txt automatically.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_1"></a>
### Please define where the JSON should be stored


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ReadJSONFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
