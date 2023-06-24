<!--TITLE: Click WebElement Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; WebElement Action &gt; Click WebElement


# Click WebElement Command


## What does this command do?
This command allows you to Click to WebElement.


## When would I want to use this command?
Use this command when you want to Click to WebElement.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebElement Variable Name](#param_0)
- [Please Select the Mouse Click Type](#param_1)
- [Optional - Please Select the WebBrowser Instance Name](#param_2)
- [Optional - Please Specify the Offset X Coordinate](#param_3)
- [Optional - Please Specify the Offset Y Coordinate](#param_4)
- [Optional - Please Select the When Fail Click](#param_5)
- [Optional - Please Select the Scroll to WebElement](#param_6)
- [Optional - Please Specify the Comment Field](#param_7)


<a id="param_0"></a>
### Please Select the WebElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebElement Variable Name</dd>
<dt>Instance Type</dt><dd>WebElement</dd>
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
<dt>Sample Usage</dt><dd><strong>Left Click</strong> or  <strong>Middle Click</strong> or  <strong>Right Click</strong> or  <strong>Left Down</strong> or  <strong>Middle Down</strong> or  <strong>Right Down</strong> or  <strong>Left Up</strong> or  <strong>Middle Up</strong> or  <strong>Right Up</strong> or  <strong>Double Left Click</strong> or  <strong>None</strong> or  <strong>Invoke Click</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>RPABrowser</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Broser</strong> command will cause an error<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPABrowser</strong> | Specify **RPABrowser** for WebBrowser Instance |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for WebBrowser Instance |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Offset X Coordinate


<dl>
<dt>What to input</dt><dd>Enter or Select the Offset X</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vXOffset}</strong></dd>
<dt>Remarks</dt><dd>It is strongly recommended to Enter a value between <strong>10</strong> and <strong>20</strong> depending on your WebBrowser.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Offset X |
| <strong>100</strong> | Specify **100** for Offset X |
| <strong>{vXOffset}</strong> | Specify Value of Variable **vXOffset** for Offset X |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Offset Y Coordinate


<dl>
<dt>What to input</dt><dd>Offset Y</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>100</strong> or <strong>{vYOffset}</strong></dd>
<dt>Remarks</dt><dd>It is strongly recommended to Enter a value between <strong>100</strong> and <strong>200</strong> depending on your WebBrowser.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Offset Y |
| <strong>100</strong> | Specify **100** for Offset Y |
| <strong>{vYOffset}</strong> | Specify Value of Variable **vYOffset** for Offset Y |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the When Fail Click


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error</strong> or  <strong>Ignore</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Scroll to WebElement


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserClickWebElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/24/23 06:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
