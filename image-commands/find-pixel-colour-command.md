<!--TITLE: Find Pixel Colour Command -->
<!-- SUBTITLE: a command in the Image group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image &gt; Find Pixel Colour


# Find Pixel Colour Command


## What does this command do?
This command searches current screen for a pixel of a certain colour inside a rectangle.


## When would I want to use this command?
Use this command when you need to find a coloured single pixel in a region on the screen.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Specify the X1 Coordinate](#param_0)
- [Optional - Please Specify the Y1 Coordinate](#param_1)
- [Optional - Please Specify the X2 Coordinate](#param_2)
- [Optional - Please Specify the Y2 Coordinate](#param_3)
- [Please Specify the Color code to search for](#param_4)
- [Please Select the Variable Name to Store Result](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Optional - Please Specify the X1 Coordinate


<dl>
<dt>What to input</dt><dd>Enter or Select the X1</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or 100 or {vXOffset}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for X |
| <strong>100</strong> | Specify **100** for X |
| <strong>{vXOffset}</strong> | Specify Value of Variable **vXOffset** for X |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Y1 Coordinate


<dl>
<dt>What to input</dt><dd>Y1</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Y |
| <strong>100</strong> | Specify **100** for Y |
| <strong>{vYOffset}</strong> | Specify Value of Variable **vYOffset** for Y |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the X2 Coordinate


<dl>
<dt>What to input</dt><dd>Enter or Select the X2</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or 100 or {vXOffset}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for X |
| <strong>100</strong> | Specify **100** for X |
| <strong>{vXOffset}</strong> | Specify Value of Variable **vXOffset** for X |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Y2 Coordinate


<dl>
<dt>What to input</dt><dd>Y2</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Y |
| <strong>100</strong> | Specify **100** for Y |
| <strong>{vYOffset}</strong> | Specify Value of Variable **vYOffset** for Y |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the Color code to search for


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: FindPixelColourCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
