<!--TITLE: Set Engine Delay Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Engine Commands &gt; Set Engine Delay


# Set Engine Delay Command


## What does this command do?
This command allows you to set delays between execution of commands in a running instance.


## When would I want to use this command?
Use this command when you want to change the execution speed between commands.


## Command Parameters
- [Set Delay between commands (in milliseconds).](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Set Delay between commands (in milliseconds).


<dl>
<dt>What to input</dt><dd>Enter a specific amount of time in milliseconds (ex. to specify 8 seconds, one would enter 8000) or specify a variable containing a value.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>250</strong> or <strong>{vVariableSpeed}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetEngineDelayCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
