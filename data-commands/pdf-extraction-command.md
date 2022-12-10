<!--TITLE: PDF Extraction Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Data Commands &gt; PDF Extraction


# PDF Extraction Command


## What does this command do?



## When would I want to use this command?



## Command Parameters
- [Please indicate the PDF file path or PDF file URL](#param_0)
- [Optional - Please select source type of PDF file (default is File Path)](#param_1)
- [Please select the variable to receive the PDF text](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the PDF file path or PDF file URL


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file or enter file URL.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.pdf or {vFilePath} or https://temp.com/myfile.pdf</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please select source type of PDF file (default is File Path)


<dl>
<dt>What to input</dt><dd>Select source type of PDF file</dd>
<dt>Sample Data</dt><dd>Select File Path, File URL</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Please select the variable to receive the PDF text


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: PDFTextExtractionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
