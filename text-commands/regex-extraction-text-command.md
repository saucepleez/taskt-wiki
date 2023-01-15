<!--TITLE: RegEx Extraction Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; RegEx Extraction Text


# RegEx Extraction Text Command


## What does this command do?
This command allows you to perform advanced string formatting using RegEx.


## When would I want to use this command?
Use this command when you want to perform an advanced RegEx extraction from a text or variable


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Please supply the value or variable](#param_0)
- [Please Input the RegEx Extractor Pattern](#param_1)
- [Please Select Matching Group Index](#param_2)
- [Please select the variable to receive the RegEx result](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Please supply the value or variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Input the RegEx Extractor Pattern


<dl>
<dt>What to input</dt><dd>Enter the RegEx extractor pattern that should be used to extract the text</dd>
<dt>Sample Usage</dt><dd><strong>\w+</strong> or <strong>^([\w-]+)</strong></dd>
<dt>Remarks</dt><dd>If an extractor splits each word in a sentence, for example, you will need to specify the associated index of the word that is required.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select Matching Group Index


<dl>
<dt>What to input</dt><dd>Define the index of the result</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>The extractor will split multiple patterns found into multiple indexes.  Test which index is required to retrieve the value or create a better/more define extractor.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please select the variable to receive the RegEx result


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
Automation Class Name: RegExExtractionTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/15/23 01:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
