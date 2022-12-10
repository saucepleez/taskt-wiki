<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Action &gt; Replace Text


# Replace Text Command


## What does this command do?
This command allows you to replace text


## When would I want to use this command?
Use this command when you want to replace existing text within text or a variable with new text


## Command Parameters
- [Please select text or variable to modify](#param_0)
- [Indicate the text to be replaced](#param_1)
- [Optional - Indicate the replacement value](#param_2)
- [Please select the variable to receive the changes](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please select text or variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Indicate the text to be replaced


<dl>
<dt>What to input</dt><dd>Enter the old value of the text that will be replaced</dd>
<dt>Sample Data</dt><dd>H or {vTextA}</dd>
<dt>Remarks</dt><dd>H in Hello would be targeted for replacement</dd>
</dl>




<a id="param_2"></a>
### Optional - Indicate the replacement value


<dl>
<dt>What to input</dt><dd>Enter the new value after replacement</dd>
<dt>Sample Data</dt><dd>J, {vTextB}</dd>
<dt>Remarks</dt><dd>H would be replaced with J to create 'Jello'<b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the changes


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
Automation Class Name: ReplaceTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
