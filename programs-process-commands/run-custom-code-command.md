<!--TITLE: Run Custom Code Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Programs/Process Commands &gt; Run Custom Code


# Run Custom Code Command


## What does this command do?
This command allows you to run C# code from the input


## When would I want to use this command?
Use this command when you want to run custom C# code commands.  The code in this command is compiled and run at runtime when this command is invoked.  This command only supports the standard framework classes.


## Command Parameters
- [Paste the C# code to execute](#param_0)
- [Optional - Supply Arguments](#param_1)
- [Optional - Select the variable to receive the output](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Paste the C# code to execute


<dl>
<dt>What to input</dt><dd>Enter the code to be executed or use the builder to create your custom C# code.  The builder contains a Hello World template that you can use to build from.</dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Supply Arguments


<dl>
<dt>What to input</dt><dd>Enter arguments that the custom code will receive during execution</dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Select the variable to receive the output


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RunCustomCodeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
