<!--TITLE: Show Message Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Misc Commands &gt; Other &gt; Show Message


# Show Message Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Message to be Displayed](#param_0)
- [Optional - Please Specify the Close After X (Seconds) - 0 to Bypass](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Specify the Message to be Displayed


<dl>
<dt>What to input</dt><dd>Enter or Select the Message</dd>
<dt>Sample Usage</dt><dd><strong>Hello World</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello World</strong> | Specify **Hello World** for Message |
| <strong>{vText}</strong> | Specify Value of Variable **vText** for Message |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Close After X (Seconds) - 0 to Bypass


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>1</strong> or <strong>0</strong> or <strong>{vTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how many seconds to display on screen.After the amount of seconds passes, the message box will be automatically closed and script will resume execution. <strong>0</strong> to remain open indefinitely or <strong>5</strong> to stay open for 5 seconds.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Close After 1 second |
| <strong>0</strong> | Don't Close Automatically |
| <strong>{vTime}</strong> | Close After Value of Variable **vTime** seconds |


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
Automation Class Name: ShowMessageCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
