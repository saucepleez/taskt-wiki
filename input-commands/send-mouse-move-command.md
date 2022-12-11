<!--TITLE: Send Mouse Move Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Input Commands &gt; Send Mouse Move


# Send Mouse Move Command


## What does this command do?
Simulates mouse movements


## When would I want to use this command?
Use this command to simulate the movement of the mouse, additionally, this command also allows you to perform a click after movement has completed.


## Command Parameters
- [Please enter the X position to move the mouse to](#param_0)
- [Please enter the Y position to move the mouse to](#param_1)
- [Optional - Please indicate mouse click type if required (defualt is None)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please enter the X position to move the mouse to


<dl>
<dt>What to input</dt><dd>Input the new horizontal coordinate of the mouse, 0 starts at the left and goes to the right</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>250</strong> or <strong>{vXPos}</strong></dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920</dd>
</dl>




<a id="param_1"></a>
### Please enter the Y position to move the mouse to


<dl>
<dt>What to input</dt><dd>Input the new horizontal coordinate of the window, 0 starts at the left and goes down</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>250</strong> or <strong>{vYPos}</strong></dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080</dd>
</dl>




<a id="param_2"></a>
### Optional - Please indicate mouse click type if required (defualt is None)


<dl>
<dt>What to input</dt><dd>Indicate the type of click required</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select from <strong>Left Click</strong>, <strong>Middle Click</strong>, <strong>Right Click</strong>, <strong>Double Left Click</strong>, <strong>Left Down</strong>, <strong>Middle Down</strong>, <strong>Right Down</strong>, <strong>Left Up</strong>, <strong>Middle Up</strong>, <strong>Right Up</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendMouseMoveCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
