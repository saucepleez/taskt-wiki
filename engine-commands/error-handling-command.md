<!--TITLE: Error Handling Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Engine Commands &gt; Error Handling


# Error Handling Command


## What does this command do?
This command specifies what to do  after an error is encountered.


## When would I want to use this command?
Use this command when you want to define how your script should behave when an error is encountered.


## Command Parameters
- [Select an action to take in the event an error occurs](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Select an action to take in the event an error occurs


<dl>
<dt>What to input</dt><dd>Select the action you want to take when you come across an error.</dd>
<dt>Sample Data</dt><dd>Stop Processing to end the script if an error is encountered or Continue Processing to continue running the script</dd>
<dt>Remarks</dt><dd>If Command allows you to specify and test if a line number encountered an error. In order to use that functionality, you must specify Continue Processing</dd>
</dl>




<a id="param_1"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ErrorHandlingCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
