<!--TITLE: Extraction Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; Extraction Text


# Extraction Text Command


## What does this command do?
This command allows you to perform advanced string extraction.


## When would I want to use this command?
Use this command when you want to extract a piece of text from a larger text or variable


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Supply the value or variable requiring extraction](#param_0)
- [Please select text extraction type](#param_1)
- [Please Specify the Extraction Parameters](#param_2)
- [Please select the variable to receive the extracted text](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Supply the value or variable requiring extraction


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please select text extraction type


<dl>
<dt>What to input</dt><dd>Select the type of extraction that is required.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Extract All After Text</strong> or  <strong>Extract All Before Text</strong> or  <strong>Extract All Between Text</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Extraction Parameters


<dl>
<dt>What to input</dt><dd>Define the required extraction parameters, which is dependent on the type of extraction.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>


#### Addtional Info about &quot;Please Specify the Extraction Parameters&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Extract All After Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All After Text &amp; Skip Past Occurences||||
|Extract All Before Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Before Text &amp; Skip Past Occurences||||
|Extract All Between Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All Between Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Between Text &amp; Skip Past Occurences||||


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please select the variable to receive the extracted text


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExtractionTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/15/23 01:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
