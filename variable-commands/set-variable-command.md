<!--TITLE: Set Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Variable Commands &gt; Set Variable


# Set Variable Command


## What does this command do?
This command allows you to modify variables.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


## Command Parameters
- [Please select a variable to modify](#param_0)
- [Please define the input to be set to above variable (ex. Hello, 1, {vNum})](#param_1)
- [Optional - Convert Variables in Input Text Above (Default is Yes)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please select a variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_1"></a>
### Please define the input to be set to above variable (ex. Hello, 1, {vNum})


<dl>
<dt>What to input</dt><dd>Enter the input that the variable's value should be set to.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>1</strong> or <strong>Hello</strong> or {vNum}</dd>
<dt>Remarks</dt><dd>You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.</dd>
</dl>




<a id="param_2"></a>
### Optional - Convert Variables in Input Text Above (Default is Yes)


<dl>
<dt>What to input</dt><dd>Select the necessary option.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>If {vNum} has '1' and you select 'Yes', variable will be assigned '1'. If you select 'No', variable will be assigned '{vNum}'.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: VariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
