<!--TITLE: Unload Task Command -->
<!-- SUBTITLE: a command in the Task Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Task Commands &gt; Unload Task


# Unload Task Command


## What does this command do?
This command runs tasks.


## When would I want to use this command?
Use this command when you want to run another task.


<a id="param_list"></a>
## Command Parameters
- [Please Select a Task to Pre-Load.  Use Run Task with the same path to execute.](#param_0)
- [Please Select the Unload Error Preference](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select a Task to Pre-Load.  Use Run Task with the same path to execute.


<dl>
<dt>What to input</dt><dd>Enter or Select the valid path to the file.</dd>
<dt>Sample Usage</dt><dd><strong>c:\temp\mytask.xml</strong> or <strong>{vScriptPath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Unload Error Preference


<dl>
<dt>What to input</dt><dd>Select the appropriate corresponding action to take once the element has been located</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error if not found</strong> or  <strong>Continue if not found</strong></dd>
<dt>Remarks</dt><dd>Selecting this field changes the parameters that will be required in the next step</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: UnloadTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/16/23 10:27 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
