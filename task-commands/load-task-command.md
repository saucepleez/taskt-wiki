<!--TITLE: Load Task Command -->
<!-- SUBTITLE: a command in the Task Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Task Commands &gt; Load Task


# Load Task Command


## What does this command do?
This command pre-loads tasks for future execution.


## When would I want to use this command?
Use this command when you want to load a task but not immediately execute it.


## Command Parameters
- [Select a task to load. After, use 'Run Task' with the same path to execute.](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Select a task to load. After, use 'Run Task' with the same path to execute.


<dl>
<dt>What to input</dt><dd>Enter or Select the valid path to the file.</dd>
<dt>Sample Data</dt><dd><strong>c:\temp\mytask.xml</strong> or <strong>{vScriptPath}</strong></dd>
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
Automation Class Name: LoadTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
