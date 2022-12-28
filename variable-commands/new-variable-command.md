<!--TITLE: New Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Variable Commands &gt; New Variable


# New Variable Command


## What does this command do?
This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Please define the name of the new variable](#param_0)
- [Please Specify the Please define the input to be set to above variable (ex. Hello, {vNum})](#param_1)
- [Please Select the Optional - Define the action to take if the variable already exists (Default is Replace If Variable Exists)](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the Please define the name of the new variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If the variable exists, the value of the old variable will be replaced with the new one</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Please define the input to be set to above variable (ex. Hello, {vNum})


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's value should be set to.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {{{vName}}}.  You can also perform basic math operations.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Optional - Define the action to take if the variable already exists (Default is Replace If Variable Exists)


<dl>
<dt>What to input</dt><dd>Select the appropriate handler from the list</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Do Nothing If Variable Exists</strong> or  <strong>Error If Variable Exists</strong> or  <strong>Replace If Variable Exists</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: AddVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/28/22 09:59 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
