<!--TITLE: New Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Variable Commands &gt; New Variable


# New Variable Command


## What does this command do?
This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


## Command Parameters
- [Please define the name of the new variable](#param_0)
- [Please define the input to be set to above variable (ex. Hello, {vNum})](#param_1)
- [Optional - Define the action to take if the variable already exists (Default is Replace If Variable Exists)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please define the name of the new variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If the variable exists, the value of the old variable will be replaced with the new one</dd>
</dl>




<a id="param_1"></a>
### Please define the input to be set to above variable (ex. Hello, {vNum})


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's value should be set to.</dd>
<dt>Sample Data</dt><dd><strong>Hello</strong> or <strong>{vNum}</strong></dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.</dd>
</dl>




<a id="param_2"></a>
### Optional - Define the action to take if the variable already exists (Default is Replace If Variable Exists)


<dl>
<dt>What to input</dt><dd>Select the appropriate handler from the list</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Do Nothing If Variable Exists</strong> or <strong>Error If Variable Exists</strong> or <strong>Replace If Variable Exists</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: AddVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
