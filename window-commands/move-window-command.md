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
<dt>Value</dt><dd>Window Names</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window title search method


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Contains</strong> or <strong>Starts with</strong> or <strong>Ends with</strong> or <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




<a id="param_2"></a>
### Please indicate the new X horizontal coordinate (pixel) for the window's location.  0 starts at the left of the screen.


<dl>
<dt>What to input</dt><dd>Input the new horizontal coordinate of the window, 0 starts at the left and goes to the right</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>0</strong> or <strong>{vXPos}</strong> or <strong>Current Position</strong></dd>
<dt>Remarks</dt><dd>This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920</dd>
</dl>




<a id="param_3"></a>
### Please indicate the new Y vertical coordinate (pixel) for the window's location.  0 starts at the top of the screen.


<dl>
<dt>What to input</dt><dd>Input the new vertical coordinate of the window, 0 starts at the top and goes downwards</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>0</strong> or <strong>{vYPos}</strong> or <strong>Current Position</strong></dd>
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
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
