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
<dt>Sample Data</dt><dd><strong>c:\temp\mytask.xml</strong> or <strong>{vScriptPath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Unload Error Preference


<dl>
<dt>What to input</dt><dd>Select the appropriate corresponding action to take once the element has been located</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select from <strong>Invoke Click</strong>, <strong>Left Click</strong>, <strong>Right Click</strong>, <strong>Middle Click</strong>, <strong>Double Left Click</strong>, <strong>Clear Element</strong>, <strong>Set Text</strong>, <strong>Get Text</strong>, <strong>Get Attribute</strong>, <strong>Wait For Element To Exist</strong>, <strong>Get Count</strong></dd>
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
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
