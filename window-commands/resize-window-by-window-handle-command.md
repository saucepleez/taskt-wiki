<!--TITLE: Resize Window By Window Handle Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Window Commands &gt; Window Handle Actions &gt; Resize Window By Window Handle


# Resize Window By Window Handle Command


## What does this command do?
This command resizes a window to a specified size.


## When would I want to use this command?
Use this command when you want to reize a window by name to a specific size on screen.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Window Handle Variable Name](#param_0)
- [Please Specify the Window Width (Pixcel)](#param_1)
- [Please Specify the Window Height (Pixcel)](#param_2)
- [Optional - Please Specify the Wait Time for the Window to Exist (sec)](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the Window Handle Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Instance Type</dt><dd>WindowHandle</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Window Width (Pixcel)


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Width</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>640 or {vWidth} or {Window.CurrentSize}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>640</strong> | Specify **640** for Width |
| <strong>{vWidth}</strong> | Specify Value of Variable **vWidth** for Width |
| <strong>{Window.CurrentSize}</strong> | Specify Current Window Width for Window Width |
| <strong>{Window.CurrentWidth}</strong> | Specify Current Window Width for Window Width |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Window Height (Pixcel)


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Height</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>480 or {vHeight} or {Window.CurrentSize}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>480</strong> | Specify **480** for Height |
| <strong>{vHeight}</strong> | Specify Value of Variable **vHeight** for Height |
| <strong>{Window.CurrentSize}</strong> | Specify Current Window Height for Window Height |
| <strong>{Window.CurrentHeight}</strong> | Specify Current Window Height for Window Height |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Wait Time for the Window to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Sample Usage</dt><dd>60 or {vTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Window is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>60</strong> | Specify **60** for Wait Time |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ResizeWindowByWindowHandleCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/07/24 09:15 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
