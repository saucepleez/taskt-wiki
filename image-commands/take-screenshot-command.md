<!--TITLE: Take Screenshot Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image Commands &gt; Take Screenshot


# Take Screenshot Command


## What does this command do?
This command takes a screenshot and saves it to a location


## When would I want to use this command?
Use this command when you want to take and save a screenshot.


<a id="param_list"></a>
## Command Parameters
- [Please Enter the Window name](#param_0)
- [Please indicate the path to save the image](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Enter the Window name


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to take a screenshot of.</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Sample Usage</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>Desktop</strong> or <strong>{vWindow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please indicate the path to save the image


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance <string>Not</string> Required</li><li>Support Extensions: </li><li>FileCounter Variable Support: Number **Not** Found First</li></ul></dd>
<dt>Sample Usage</dt><dd><strong>c:\Temp\image.png</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>If file does not contain extensin, suppliment png extension.
If file does not contain folder path, file will be saved in the same folder as script file.
If file path contains FileCounter variable, it will be replaced by a number that will become the name of a non-existent file.</dd>
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
Automation Class Name: ScreenshotCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
