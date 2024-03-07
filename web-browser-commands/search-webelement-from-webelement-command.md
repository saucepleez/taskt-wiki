<!--TITLE: Search WebElement From WebElement Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Search WebElement &gt; Search WebElement From WebElement


# Search WebElement From WebElement Command


## What does this command do?
This command allows you to search WebElement from WebElement.


## When would I want to use this command?
Use this command when you want to get WebElement from WebElement.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebElement Variable Name](#param_0)
- [Please Select the Element Search Method](#param_1)
- [Please Specify the Element Search Parameter](#param_2)
- [Please Specify the Element Index](#param_3)
- [Please Select the WebElement Variable Name](#param_4)
- [Optional - Please Specify the Wait Time for the WebElement to Exist (sec)](#param_5)
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
### Please Select the Element Search Method


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Find Element By XPath</strong> or  <strong>Find Element By ID</strong> or  <strong>Find Element By Name</strong> or  <strong>Find Element By Tag Name</strong> or  <strong>Find Element By Class Name</strong> or  <strong>Find Element By CSS Selector</strong> or  <strong>Find Element By Link Text</strong> or  <strong>Find Elements By XPath</strong> or  <strong>Find Elements By ID</strong> or  <strong>Find Elements By Name</strong> or  <strong>Find Elements By Tag Name</strong> or  <strong>Find Elements By Class Name</strong> or  <strong>Find Elements By CSS Selector</strong> or  <strong>Find Elements By Link Text</strong></dd>
<dt>Remarks</dt><dd>Select the specific search type that you want to use to isolate the element in the web page.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Element Search Parameter


<dl>
<dt>What to input</dt><dd>Enter or Select the Element Search Parameter</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Specifies the parameter text that matches to the element based on the previously selected search type.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Element Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Element Index</dd>
<dt>Sample Usage</dt><dd>0 or 1 or {vIndex}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify the First Element Index |
| <strong>1</strong> | Specify **1** for Element Index |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Element Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Select the WebElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebElement Variable Name</dd>
<dt>Instance Type</dt><dd>WebElement</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
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


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Wait Time for the WebElement to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Sample Usage</dt><dd>120 or {vTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the WebElement is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>120</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>120</strong> | Specify **120** for Wait Time |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Wait Time |


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
Automation Class Name: SeleniumBrowserSearchWebElementFromWebElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/07/24 09:15 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
