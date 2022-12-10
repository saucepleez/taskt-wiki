<!--TITLE: Show Message Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Misc Commands &gt; Other &gt; Show Message


# Show Message Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


## Command Parameters
- [Please Enter the message to be displayed.](#param_0)
- [Optional - Close After X (Seconds) - 0 to bypass (Default is 0)](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the message to be displayed.


<dl>
<dt>What to input</dt><dd>Specify any text that should be displayed on screen.  You may also include variables for display purposes.</dd>
<dt>Sample Data</dt><dd>Hello World or {vMyText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Close After X (Seconds) - 0 to bypass (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify how many seconds to display on screen. After the amount of seconds passes, the message box will be automatically closed and script will resume execution.</dd>
<dt>Sample Data</dt><dd>0 or {vTime}</dd>
<dt>Remarks</dt><dd>0 to remain open indefinitely or 5 to stay open for 5 seconds.<b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MessageBoxCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
