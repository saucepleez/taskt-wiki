<!--TITLE: Stop Process Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Programs/Process Commands &gt; Stop Process


# Stop Process Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


## Command Parameters
- [Enter the process name to be stopped (ex. calc, notepad, {vPath})](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Enter the process name to be stopped (ex. calc, notepad, {vPath})


<dl>
<dt>What to input</dt><dd>Provide the program process name as it appears as a process in Windows Task Manager</dd>
<dt>Sample Data</dt><dd>notepad or calc or {vPath}</dd>
<dt>Remarks</dt><dd>The program name may vary from the actual process name.  You can use Thick App commands instead to close an application window.</dd>
</dl>




<a id="param_1"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: StopProcessCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
