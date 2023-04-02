<!--TITLE: Execute Script Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Execute Script


# Execute Script Command


## What does this command do?
This command allows you to execute a script in a Selenium web browser session.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Optional - Please Select the JavaScript Code Type](#param_1)
- [Please Specify the JavaScript Code](#param_2)
- [Optional - Please Specify the Timeout in Seconds](#param_3)
- [Optional - Please Specify the Argument](#param_4)
- [Optional - Please Select the Variable Name to Recieve Result Value](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>RPABrowser</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Broser</strong> command will cause an error</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPABrowser</strong> | Specify **RPABrowser** for WebBrowser Instance |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for WebBrowser Instance |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the JavaScript Code Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Code</strong> or  <strong>File</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Code</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Code</strong> | Use Specfied JavaScript Code |
| <strong>File</strong> | Use Specfied JavaScript File |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the JavaScript Code


<dl>
<dt>What to input</dt><dd>Enter or Select the JavaScript</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>return (2);</strong> or <strong>c:\js\mycode.js</strong> or <strong>{vCode}</strong></dd>
<dt>Remarks</dt><dd>When Selected <strong>Code</strong>, plese Enter the JavaScript Code.
When Selected <strong>File</strong>, please Enter the JavaScript File Path.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>return (2);</strong> | Specify the JavaScript Code |
| <strong>c:\js\mycode.js</strong> | Specify the JavaScript File Path |
| <strong>{vCode}</strong> | Specify the Variable Value **vCode** for JavaScript Code or JavaScript File Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Timeout in Seconds


<dl>
<dt>What to input</dt><dd>Enter or Select the Timeout in Seconds</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>10</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>When Value is Less Than or Equals to <strong>0</strong>, this means Waiting until JavaScript is finished.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Timeout. This means Waiting until JavaScript is finished. |
| <strong>10</strong> | Specify **10** for Timeout |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Timeout |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Argument


<dl>
<dt>What to input</dt><dd>Enter or Select the Argument</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>The value of the argument can be obtained with 'arguments[0]' in code.<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify **0** for Argument |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Argument |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the Variable Name to Recieve Result Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
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
Automation Class Name: SeleniumBrowserExecuteScriptCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
