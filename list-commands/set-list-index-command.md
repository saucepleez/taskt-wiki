<!--TITLE: Set List Index Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
List Commands &gt; Other &gt; Set List Index


# Set List Index Command


## What does this command do?
This command allows you to modify List Index.


## When would I want to use this command?
Use this command when you want to modify List Index.  You can even use variables to modify other variables.


## Command Parameters
- [Please select a List Variable Name to modify](#param_0)
- [Please set the current Index of the List](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please select a List Variable Name to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vList or {vList}</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_1"></a>
### Please set the current Index of the List


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's index should be set to.</dd>
<dt>Sample Data</dt><dd>0 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetListIndexCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
