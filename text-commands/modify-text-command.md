<!--TITLE: Modify Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Action &gt; Modify Text


# Modify Text Command


## What does this command do?
This command allows you to trim Text, convert Text, etc.


## When would I want to use this command?
Use this command when you want to trim Text, convert Text, etc.


## Command Parameters
- [Please Supply the Text or Variable to modify](#param_0)
- [Please Select Modify Method](#param_1)
- [Please select the variable to receive the changes](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Supply the Text or Variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select Modify Method


<dl>
<dt>What to input</dt><dd>Indicate if only so many characters should be kept</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the variable to receive the changes


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
Automation Class Name: ModifyTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
