<!--TITLE: Select Option For WebElement Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; WebElement Action &gt; Select Option For WebElement


# Select Option For WebElement Command


## What does this command do?
This command allows you to Select an Option for WebElement.


## When would I want to use this command?
Use this command when you want to Select an Option for WebElement.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebElement Variable Name](#param_0)
- [Please Selection Type](#param_1)
- [Please Specify the Option Value to Select](#param_2)
- [Optional - Please Select the When Fail Select Action](#param_3)
- [Optional - Please Select the Scroll to WebElement](#param_4)
- [Optional - Please Select the WebBrowser Instance Name](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Select the WebElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebElement Variable Name</dd>
<dt>Instance Type</dt><dd>WebElement</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vElement or {vElement}</dd>
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
### Please Selection Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Select By Index</strong> or  <strong>Select By Text</strong> or  <strong>Select By Value</strong> or  <strong>Deselect By Index</strong> or  <strong>Deselect By Text</strong> or  <strong>Deselect By Value</strong> or  <strong>Deselect All</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Option Value to Select


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>Hello or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** for Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When Fail Select Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error</strong> or  <strong>Ignore</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Scroll to WebElement


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>RPABrowser or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Broser</strong> command will cause an error<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPABrowser</strong> | Specify **RPABrowser** for WebBrowser Instance |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for WebBrowser Instance |


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
Automation Class Name: SeleniumBrowserSelectOptionForWebElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
