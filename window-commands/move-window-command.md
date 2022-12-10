<!--TITLE: Move Window Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Window Commands &gt; Window Actions &gt; Move Window


# Move Window Command


## What does this command do?
This command moves a window to a specified location on screen.


## When would I want to use this command?
Use this command when you want to move an existing window by name to a certain point on the screen.


## Command Parameters
- [Please enter or select the window that you want to move.](#param_0)
- [Optional - Window title search method](#param_1)
- [Please indicate the new X horizontal coordinate (pixel) for the window's location.  0 starts at the left of the screen.](#param_2)
- [Please indicate the new Y vertical coordinate (pixel) for the window's location.  0 starts at the top of the screen.](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please enter or select the window that you want to move.


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to move.</dd>
<dt>Sample Data</dt><dd>Untitled - Notepad or Current Window or {vWindow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window title search method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Contains</dd>
</dl>




<a id="param_2"></a>
### Please indicate the new X horizontal coordinate (pixel) for the window's location.  0 starts at the left of the screen.


<dl>
<dt>What to input</dt><dd>Input the new horizontal coordinate of the window, 0 starts at the left and goes to the right</dd>
<dt>Sample Data</dt><dd>0 or {vXPos} or Current Position</dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920</dd>
</dl>




<a id="param_3"></a>
### Please indicate the new Y vertical coordinate (pixel) for the window's location.  0 starts at the top of the screen.


<dl>
<dt>What to input</dt><dd>Input the new vertical coordinate of the window, 0 starts at the top and goes downwards</dd>
<dt>Sample Data</dt><dd>0 or {vYPos} or Current Position</dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MoveWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
