<!--TITLE: Resize Window Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Window Commands &gt; Window Actions &gt; Resize Window


# Resize Window Command


## What does this command do?
This command resizes a window to a specified size.


## When would I want to use this command?
Use this command when you want to reize a window by name to a specific size on screen.


## Command Parameters
- [Please enter or select the window that you want to resize.](#param_0)
- [Optional - Window title search method](#param_1)
- [Please indicate the new required width (pixel) of the window.](#param_2)
- [Please indicate the new required height (pixel) of the window.](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please enter or select the window that you want to resize.


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to resize.</dd>
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
### Please indicate the new required width (pixel) of the window.


<dl>
<dt>What to input</dt><dd>Input the new width size of the window</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>640</strong> or <strong>{vWidth}</strong></dd>
<dt>Remarks</dt><dd>This number is limited by your resolution. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid width range could be 0-1920</dd>
</dl>




<a id="param_3"></a>
### Please indicate the new required height (pixel) of the window.


<dl>
<dt>What to input</dt><dd>Input the new height size of the window</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>480</strong> or <strong>{vHeight}</strong></dd>
<dt>Remarks</dt><dd>This number is limited by your resolution. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid height range could be 0-1080</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ResizeWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
