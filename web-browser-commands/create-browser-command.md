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
<dt>Sample Data</dt><dd>myInstance or seleniumInstance</dd>
<dt>Remarks</dt><dd>Please install web browser before using this command.</dd>
</dl>




<a id="param_1"></a>
### Optional - Instance Tracking (after task ends) (Default is Forget Instance)


<dl>
<dt>What to input</dt><dd>Specify if taskt should remember this instance name after the script has finished executing.</dd>
<dt>Sample Data</dt><dd>Select Forget Instance to forget the instance or Keep Instance Alive to allow subsequent tasks to call the instance by name.</dd>
<dt>Remarks</dt><dd>Calling the Close Browser command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.<b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Optional - Please Select a Window State (Default is Normal)


<dl>
<dt>What to input</dt><dd>Select the window state that the browser should start up with.</dd>
<dt>Sample Data</dt><dd>Select Normal to start the browser in normal mode or Maximize to start the browser in maximized mode.</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Please specify Selenium command line options


<dl>
<dt>What to input</dt><dd>Select optional options to be passed to the Selenium command.</dd>
<dt>Sample Data</dt><dd>user-data-dir=c:\users\public\SeleniumTasktProfile</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Please Select a Browser Engine Type (Default is Chrome)


<dl>
<dt>What to input</dt><dd>Select the window state that the browser should start up with.</dd>
<dt>Sample Data</dt><dd>Select Edge or Chrome or Firefox of IE</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_5"></a>
### Optional - Please Select Browser Binary Path (Default is Empty)


<dl>
<dt>What to input</dt><dd>Select Browser Binary Path</dd>
<dt>Sample Data</dt><dd>C:\temp\BrowserPath.exe or {vPath}</dd>
<dt>Remarks</dt><dd>Edge and IE is not supported.
If you use a fixed web browser version, use this parameter.<b>Optional</b><br></dd>
</dl>




<a id="param_6"></a>
### Optional - Please Select WebDriver Path (Default is Empty)


<dl>
<dt>What to input</dt><dd>Select WebDriver Binary Path</dd>
<dt>Sample Data</dt><dd>C:\temp\WebDriverPath.exe or {vPath}</dd>
<dt>Remarks</dt><dd>IE is not supported.
If you use a fixed web browser version, use this parameter.<b>Optional</b><br></dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
