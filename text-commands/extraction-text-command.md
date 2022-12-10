<!--TITLE: Extraction Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Action &gt; Extraction Text


# Extraction Text Command


## What does this command do?
This command allows you to perform advanced string extraction.


## When would I want to use this command?
Use this command when you want to extract a piece of text from a larger text or variable


## Command Parameters
- [Supply the value or variable requiring extraction](#param_0)
- [Please select text extraction type](#param_1)
- [Extraction Parameters](#param_2)
- [Please select the variable to receive the extracted text](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Supply the value or variable requiring extraction


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select text extraction type


<dl>
<dt>What to input</dt><dd>Select the type of extraction that is required.</dd>
<dt>Sample Data</dt><dd>Select from Before Text, After Text, Between Text</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Extraction Parameters


<dl>
<dt>What to input</dt><dd>Define the required extraction parameters, which is dependent on the type of extraction.</dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>


### Addtional Info about &quot;Extraction Parameters&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Extract All After Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All After Text &amp; Skip Past Occurences||||
|Extract All Before Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Before Text &amp; Skip Past Occurences||||
|Extract All Between Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All Between Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Between Text &amp; Skip Past Occurences||||


<a id="param_3"></a>
### Please select the variable to receive the extracted text


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
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
Automation Class Name: ExtractionTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
