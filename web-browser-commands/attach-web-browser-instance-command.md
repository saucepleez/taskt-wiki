<!--TITLE: Attach Web Browser Instance Command -->
<!-- SUBTITLE: a command in the Web Browser group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser &gt; Instance &gt; Attach Web Browser Instance


# Attach Web Browser Instance Command


## What does this command do?
This command allows you to Attach to the running WebBrowser and Create an Instance.


## When would I want to use this command?
Use this command when you want to Attach to the running WebBrowser and Create an Instance.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Optional - Please Select the Web Browser Type](#param_1)
- [Optional - Please Specify the Debugger Address (Edge/Chrome only)](#param_2)
- [Optional - Please Specify the Debugger Port (Edge/Chrome only)](#param_3)
- [Optional - Please Specify the Web Driver Binary Path](#param_4)
- [Optional - Please Select the Hide Terminal Window](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Value</dt><dd>WebBrowser Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>RPABrowser or {vInstance}</dd>
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
### Optional - Please Select the Web Browser Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Edge</strong> or  <strong>Chrome</strong> or  <strong>Firefox</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Chrome</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Debugger Address (Edge/Chrome only)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>127.0.0.1</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Debugger Port (Edge/Chrome only)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>9222</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Web Driver Binary Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Web Driver Binary Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>C:\temp\WebDriverPath.exe or {vBrowserPath}</dd>
<dt>Remarks</dt><dd>When path is Empty, taskt uses default WebDriver.
IE is not supported.
If you use a fixed web browser version, use this parameter.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Empty</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\WebDriverPath.exe</strong> | Specify **C:\temp\WebDriverPath.exe** for WebDriver Path |
| <strong>{vBrowserPath}</strong> | Specify Value of Variable **vBrowserPath** for WebDriver Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the Hide Terminal Window


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




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
Automation Class Name: SeleniumBrowserAttachCreateWebBrowserInstanceCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
