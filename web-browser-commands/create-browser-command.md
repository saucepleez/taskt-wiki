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


## Command Parameters
- [Please Enter the instance name (ex. myInstance, {vInstance})](#param_0)
- [Optional - Instance Tracking (after task ends) (Default is Forget Instance)](#param_1)
- [Optional - Please Select a Window State (Default is Normal)](#param_2)
- [Optional - Please specify Selenium command line options](#param_3)
- [Optional - Please Select a Browser Engine Type (Default is Chrome)](#param_4)
- [Optional - Please Select Browser Binary Path (Default is Empty)](#param_5)
- [Optional - Please Select WebDriver Path (Default is Empty)](#param_6)
- [Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstance, {vInstance})


<dl>
<dt>What to input</dt><dd>Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>seleniumInstance</strong></dd>
<dt>Remarks</dt><dd>Please install web browser before using this command.</dd>
</dl>




<a id="param_1"></a>
### Optional - Instance Tracking (after task ends) (Default is Forget Instance)


<dl>
<dt>What to input</dt><dd>Specify if taskt should remember this instance name after the script has finished executing.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Forget Instance</strong> to forget the instance or <strong>Keep Instance Alive</strong> to allow subsequent tasks to call the instance by name.</dd>
<dt>Remarks</dt><dd>Calling the <strong>Close Browser</strong> command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Optional - Please Select a Window State (Default is Normal)


<dl>
<dt>What to input</dt><dd>Select the window state that the browser should start up with.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Normal</strong> to start the browser in normal mode or <strong>Maximize</strong> to start the browser in maximized mode.</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Please specify Selenium command line options


<dl>
<dt>What to input</dt><dd>Select optional options to be passed to the Selenium command.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>user-data-dir=c:\users\public\SeleniumTasktProfile</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Please Select a Browser Engine Type (Default is Chrome)


<dl>
<dt>What to input</dt><dd>Select the window state that the browser should start up with.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Edge</strong> or <strong>Chrome</strong> or <strong>Firefox</strong> of <strong>IE</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_5"></a>
### Optional - Please Select Browser Binary Path (Default is Empty)


<dl>
<dt>What to input</dt><dd>Select Browser Binary Path</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>C:\temp\BrowserPath.exe</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>Edge and IE is not supported.
If you use a fixed web browser version, use this parameter.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_6"></a>
### Optional - Please Select WebDriver Path (Default is Empty)


<dl>
<dt>What to input</dt><dd>Select WebDriver Binary Path</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>C:\temp\WebDriverPath.exe</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>IE is not supported.
If you use a fixed web browser version, use this parameter.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
