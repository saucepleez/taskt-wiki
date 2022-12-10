<!--TITLE: Substring Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Action &gt; Substring Text


# Substring Text Command


## What does this command do?
This command allows you to trim a Text


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


## Command Parameters
- [Please select a variable or text](#param_0)
- [Please specify Start from Position](#param_1)
- [Optional - Please specify Extract Length (-1 to keep remainder)](#param_2)
- [Please select the variable to receive the Result](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please select a variable or text


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify Start from Position


<dl>
<dt>What to input</dt><dd>Indicate the starting position within the string</dd>
<dt>Sample Data</dt><dd>1 or {vPosition}</dd>
<dt>Remarks</dt><dd>0 for beginning, 1 for first character, etc.</dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify Extract Length (-1 to keep remainder)


<dl>
<dt>What to input</dt><dd>Indicate if only so many characters should be kept</dd>
<dt>Sample Data</dt><dd>1 or -1 or {vLength}</dd>
<dt>Remarks</dt><dd>-1 to keep remainder, 1 for 1 position after start index.<b>Optional</b><br>Default Value is -1</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the Result


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
Automation Class Name: SubstringTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
