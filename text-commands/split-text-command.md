<!--TITLE: Split Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Action &gt; Split Text


# Split Text Command


## What does this command do?
This command allows you to split a Text


## When would I want to use this command?
Use this command when you want to split a single Text or variable into multiple items


## Command Parameters
- [Please select variable or text to split](#param_0)
- [Please specify Input Delimiter (ex. [crLF] for new line, [chars] for each char, ',' , {vChar})](#param_1)
- [Please select the list variable which will contain the results](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please select variable or text to split


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify Input Delimiter (ex. [crLF] for new line, [chars] for each char, ',' , {vChar})


<dl>
<dt>What to input</dt><dd>Declare the character that will be used to seperate. [crLF] can be used for line breaks and [chars] can be used to split each digit/letter</dd>
<dt>Sample Data</dt><dd>[crLF], [chars], ',' (comma - with no single quote wrapper)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the list variable which will contain the results


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
Automation Class Name: SplitTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
