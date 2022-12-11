<!--TITLE: Get Word Length Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Check/Get &gt; Get Word Length


# Get Word Length Command


## What does this command do?
This command allows you to retrieve the length of a Text or Variable.


## When would I want to use this command?
Use this command when you want to find the length of a Text or Variable


## Command Parameters
- [Supply the Text or Variable to find length of](#param_0)
- [Please select the variable to receive the length](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Supply the Text or Variable to find length of


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>Hello</strong> or <strong>{vSomeVariable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the variable to receive the length


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetWordLengthCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
