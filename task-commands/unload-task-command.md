<!--TITLE: Unload Task Command -->
<!-- SUBTITLE: a command in the Task Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Task Commands &gt; Unload Task


# Unload Task Command


## What does this command do?
This command runs tasks.


## When would I want to use this command?
Use this command when you want to run another task.


## Command Parameters
- [Select a Task to Pre-Load.  Use Run Task with the same path to execute.](#param_0)
- [Unload Error Preference](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Select a Task to Pre-Load.  Use Run Task with the same path to execute.


<dl>
<dt>What to input</dt><dd>Enter or Select the valid path to the file.</dd>
<dt>Sample Data</dt><dd>c:\temp\mytask.xml or {vScriptPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Unload Error Preference


<dl>
<dt>What to input</dt><dd>Select the appropriate corresponding action to take once the element has been located</dd>
<dt>Sample Data</dt><dd>Select from Invoke Click, Left Click, Right Click, Middle Click, Double Left Click, Clear Element, Set Text, Get Text, Get Attribute, Wait For Element To Exist, Get Count</dd>
<dt>Remarks</dt><dd>Selecting this field changes the parameters that will be required in the next step</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: UnloadTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
