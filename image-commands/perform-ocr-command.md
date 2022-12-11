<!--TITLE: Perform OCR Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image Commands &gt; Perform OCR


# Perform OCR Command


## What does this command do?
This command allows you to covert an image file into text for parsing.


## When would I want to use this command?
Use this command when you want to convert an image into text.  You can then use additional commands to parse the data.


## Command Parameters
- [Select Image to OCR](#param_0)
- [Apply OCR Result To Variable](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Select Image to OCR


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the image file.</dd>
<dt>Sample Data</dt><dd><strong>c:\temp\myimages.png</strong> or <strong>{vFileName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Apply OCR Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OCRCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
