<!--TITLE: Create Browser Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Instance &gt; Create Browser


# Create Browser Command


## What does this command do?
This command allows you to create a new Selenium web browser session which enables automation for websites.


## When would I want to use this command?
Use this command when you want to create a browser that will eventually perform web automation such as checking an internal company intranet site to retrieve data.
If this command does not work, please check your browser version, and WebDriver version.
You can check the WebDriver version with "foo.exe -v" in command prompt.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Optional - Please Select the Instance Tracking (After task ends)](#param_1)
- [Optional - Please Select the Window State](#param_2)
- [Optional - Please Specify the WebBrowser Command Line Options](#param_3)
- [Optional - Please Select the WebBrowser Type](#param_4)
- [Optional - Please Specify the WebBrowser Binary Path](#param_5)
- [Optional - Please Specify the WebDriver Binary Path](#param_6)
- [Optional - Please Specify the Comment Field](#param_7)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
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
### Optional - Please Select the Instance Tracking (After task ends)


<dl>
<dt>What to input</dt><dd>Specify if taskt should remember this instance name after the script has finished executing.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Forget Instance</strong> or  <strong>Keep Instance Alive</strong></dd>
<dt>Remarks</dt><dd>Calling the <strong>Close Browser</strong> command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Forget Instance</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Forget Instance</strong> | Forget the instance After tasks ends |
| <strong>Keep Instance Alive</strong> | Allow subsequent tasks to call the instance by name |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Window State


<dl>
<dt>What to input</dt><dd>Select the window state that the browser should start up with.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Normal</strong> or  <strong>Maximize</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Normal</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Normal</strong> | Start the WebBrowser in Normal mode |
| <strong>Maximize</strong> | Start the WebBrowser in maximized mode |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the WebBrowser Command Line Options


<dl>
<dt>What to input</dt><dd>Enter or Select the Command Line Options</dd>
<dt>Sample Usage</dt><dd>user-data-dir=c:\users\public\SeleniumTasktProfile</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the WebBrowser Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Edge</strong> or  <strong>Chrome</strong> or  <strong>Firefox</strong> or  <strong>IE</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Chrome</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the WebBrowser Binary Path


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Binary Path</dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\BrowserPath.exe</strong> or <strong>{vBrowserPath}</strong></dd>
<dt>Remarks</dt><dd>When path is Empty, taskt try open default path.
Edge and IE is not supported.
If you use a fixed web browser version, use this parameter.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Empty</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\BrowserPath.exe</strong> | Specify **C:\temp\BrowserPath.exe** for WebBrowser Path |
| <strong>{vBrowserPath}</strong> | Specify Value of Variable **vBrowserPath** for WebBrowser Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the WebDriver Binary Path


<dl>
<dt>What to input</dt><dd>Enter or Select the WebDriver Binary Path</dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\WebDriverPath.exe</strong> or <strong>{vBrowserPath}</strong></dd>
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
Automation Class Name: SeleniumBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
