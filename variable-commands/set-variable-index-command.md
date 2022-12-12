<!--TITLE: Set Variable Index Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Variable Commands &gt; Set Variable Index


# Set Variable Index Command


## What does this command do?
This command allows you to modify variables.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


## Command Parameters
- [Please Specify the Please select a variable to modify](#param_0)
- [Please Specify the Please set the current index of the variable (ex. 1, 2, {vNum})](#param_1)
- [Please Specify the Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Specify the Please select a variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_1"></a>
### Please Specify the Please set the current index of the variable (ex. 1, 2, {vNum})


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's index should be set to.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {{{vName}}}.  You can also perform basic math operations.</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetVariableIndexCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
