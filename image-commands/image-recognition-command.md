<!--TITLE: Image Recognition Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image Commands &gt; Image Recognition


# Image Recognition Command


## What does this command do?
This command attempts to find an existing image on screen.


## When would I want to use this command?
Use this command when you want to attempt to locate an image on screen.  You can subsequently take actions such as move the mouse to the location or perform a click.  This command generates a fingerprint from the comparison image and searches for it in on the desktop.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Capture the search image](#param_0)
- [Optional - Please Specify the Offset X Coordinate (Default is 0)](#param_1)
- [Optional - Please Specify the Offset Y Coordinate (Default is 0)](#param_2)
- [Optional - Please indicate mouse click type if required (Default is None)](#param_3)
- [Optional - Please Specify the Timeout (seconds, 0 for unlimited search time) (Default is 30)](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Specify the Capture the search image


<dl>
<dt>What to input</dt><dd>Use the tool to capture an image</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>The image will be used as the image to be found on screen.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Offset X Coordinate (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify if an offset is required.</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vXOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse X pixels to the right of the location of the image<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Offset Y Coordinate (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify if an offset is required.</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vYOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse X pixels down from the top of the location of the image<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please indicate mouse click type if required (Default is None)


<dl>
<dt>What to input</dt><dd>Indicate the type of click required</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>None</strong> or  <strong>Left Click</strong> or  <strong>Middle Click</strong> or  <strong>Right Click</strong> or  <strong>Left Down</strong> or  <strong>Middle Down</strong> or  <strong>Right Down</strong> or  <strong>Left Up</strong> or  <strong>Middle Up</strong> or  <strong>Right Up</strong> or  <strong>Double Left Click</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Timeout (seconds, 0 for unlimited search time) (Default is 30)


<dl>
<dt>What to input</dt><dd>Enter a timeout length if required.</dd>
<dt>Sample Usage</dt><dd><strong>30</strong> or <strong>0</strong> or <strong>{vTimeout}</strong></dd>
<dt>Remarks</dt><dd>Search times become excessive for colors such as white. For best results, capture a large color variance on screen, not just a white block.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ImageRecognitionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
