<!--TITLE: Add List Item Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List Commands &gt; List Item &gt; Add List Item


# Add List Item Command


## What does this command do?
This command allows you to add list item.


## When would I want to use this command?
Use this command when you want to add list item.  You can even use variables to modify other variables.


## Command Parameters
- [Please select a List Variable Name to modify](#param_0)
- [Please define the input to be added to the variable](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please select a List Variable Name to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vList</strong> or <strong>{vList}</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_1"></a>
### Please define the input to be added to the variable


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's value should be set to.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>Hello</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.</dd>
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
Automation Class Name: AddListItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
