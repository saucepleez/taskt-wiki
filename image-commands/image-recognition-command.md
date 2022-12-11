<!--TITLE: Image Recognition Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image Commands &gt; Image Recognition


# Image Recognition Command


## What does this command do?
This command attempts to find an existing image on screen.


## When would I want to use this command?
Use this command when you want to attempt to locate an image on screen.  You can subsequently take actions such as move the mouse to the location or perform a click.  This command generates a fingerprint from the comparison image and searches for it in on the desktop.


## Command Parameters
- [Capture the search image](#param_0)
- [Optional - Offset X Coordinate (Default is 0)](#param_1)
- [Optional - Offset Y Coordinate (Default is 0)](#param_2)
- [Optional - Please indicate mouse click type if required (Default is None)](#param_3)
- [Optional - Timeout (seconds, 0 for unlimited search time) (Default is 30)](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Capture the search image


<dl>
<dt>What to input</dt><dd>Use the tool to capture an image</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>The image will be used as the image to be found on screen.</dd>
</dl>




<a id="param_1"></a>
### Optional - Offset X Coordinate (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify if an offset is required.</dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vXOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse X pixels to the right of the location of the image<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Optional - Offset Y Coordinate (Default is 0)


<dl>
<dt>What to input</dt><dd>Specify if an offset is required.</dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vYOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse X pixels down from the top of the location of the image<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Please indicate mouse click type if required (Default is None)


<dl>
<dt>What to input</dt><dd>Indicate the type of click required</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select from <strong>Left Click</strong>, <strong>Middle Click</strong>, <strong>Right Click</strong>, <strong>Double Left Click</strong>, <strong>Left Down</strong>, <strong>Middle Down</strong>, <strong>Right Down</strong>, <strong>Left Up</strong>, <strong>Middle Up</strong>, <strong>Right Up</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Timeout (seconds, 0 for unlimited search time) (Default is 30)


<dl>
<dt>What to input</dt><dd>Enter a timeout length if required.</dd>
<dt>Sample Data</dt><dd><strong>30</strong> or <strong>0</strong> or <strong>{vTimeout}</strong></dd>
<dt>Remarks</dt><dd>Search times become excessive for colors such as white. For best results, capture a large color variance on screen, not just a white block.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ImageRecognitionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
