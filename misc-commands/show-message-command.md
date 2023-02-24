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
- [Please Enter the message to be displayed.](#param_0)
- [Optional - Please Specify the Close After X (Seconds) - 0 to bypass (Default is 0)](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Enter the message to be displayed.


<dl>
<dt>What to input</dt><dd>Specify any text that should be displayed on screen.  You may also include variables for display purposes.</dd>
<dt>Sample Usage</dt><dd><strong>Hello World</strong> or <strong>{vMyText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Close After X (Seconds) - 0 to bypass (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify how many seconds to display on screen. After the amount of seconds passes, the message box will be automatically closed and script will resume execution.</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>{vTime}</strong></dd>
<dt>Remarks</dt><dd><strong>0</strong> to remain open indefinitely or <strong>5</strong> to stay open for 5 seconds.<br><br>
<strong>Optional</strong><br></dd>
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
Automation Class Name: MessageBoxCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/24/23 08:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
