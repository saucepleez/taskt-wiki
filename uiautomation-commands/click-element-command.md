<!--TITLE: Click Element Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Element Action &gt; Click Element


# Click Element Command


## What does this command do?
This command allows you to Click AutomationElement.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the AutomationElement Variable Name](#param_0)
- [Please Select the Mouse Click Type](#param_1)
- [Optional - Please Specify the Offset X Coordinate](#param_2)
- [Optional - Please Specify the Offset Y Coordinate](#param_3)
- [Optional - Please Select the Activate Window before Click](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Select the AutomationElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the AutomationElement Variable Name</dd>
<dt>Instance Type</dt><dd>AutomationElement</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vElement</strong> or <strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vElement</strong> | Specify Value of Variable **vElement** |
| <strong>{vElement}</strong> | Specify Value of Variable **vElement** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Mouse Click Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Left Click</strong> or  <strong>Middle Click</strong> or  <strong>Right Click</strong> or  <strong>Left Down</strong> or  <strong>Middle Down</strong> or  <strong>Right Down</strong> or  <strong>Left Up</strong> or  <strong>Middle Up</strong> or  <strong>Right Up</strong> or  <strong>Double Left Click</strong> or  <strong>None</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Offset X Coordinate


<dl>
<dt>What to input</dt><dd>Enter or Select the Offset X</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vXOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse X pixels to the right of the location of the target<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Offset X |
| <strong>100</strong> | Specify **100** for Offset X |
| <strong>{vXOffset}</strong> | Specify Value of Variable **vXOffset** for Offset X |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Offset Y Coordinate


<dl>
<dt>What to input</dt><dd>Offset Y</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vYOffset}</strong></dd>
<dt>Remarks</dt><dd>This will move the mouse Y pixels down from the top of the location of the target<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Offset Y |
| <strong>100</strong> | Specify **100** for Offset Y |
| <strong>{vYOffset}</strong> | Specify Value of Variable **vYOffset** for Offset Y |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Activate Window before Click


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Yes</strong></dd>
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
Automation Class Name: UIAutomationClickElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/13/23 08:50 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
