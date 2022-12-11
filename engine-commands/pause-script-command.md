<!--TITLE: Pause Script Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Engine Commands &gt; Pause Script


# Pause Script Command


## What does this command do?
This command pauses the script for a set amount of time specified in milliseconds.


## When would I want to use this command?
Use this command when you want to pause your script for a specific amount of time.  After the specified time is finished, the script will resume execution.


## Command Parameters
- [Amount of time to pause for (in milliseconds). (ex. 2500, {vWait})](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Amount of time to pause for (in milliseconds). (ex. 2500, {vWait})


<dl>
<dt>What to input</dt><dd>Enter a specific amount of time in milliseconds (ex. to specify 8 seconds, one would enter 8000) or specify a variable containing a value.</dd>
<dt>Sample Data</dt><dd><strong>8000</strong> or <strong>{vVariableWaitTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: PauseCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
