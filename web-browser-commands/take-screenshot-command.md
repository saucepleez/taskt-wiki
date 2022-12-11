<!--TITLE: Take Screenshot Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Take Screenshot


# Take Screenshot Command


## What does this command do?
This command allows you to take a screenshot in Selenium web browser session.


## When would I want to use this command?
Use this command when you want to take a screenshot from the current displayed webpage within the web browser.


## Command Parameters
- [Please Enter the instance name (ex. myInstance, {vInstance})](#param_0)
- [Please define folder where the screenshot should be stored (ex. C:\screenshots, {vPath})](#param_1)
- [Please define the screenshot file name (no extension needed) (ex. screenshot_001, {vName})](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstance, {vInstance})


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Browser</strong> command</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please define folder where the screenshot should be stored (ex. C:\screenshots, {vPath})


<dl>
<dt>What to input</dt><dd>Enter folder path or select folder from the list to define where the screenshot should be stored</dd>
<dt>Sample Data</dt><dd>*<em>C:\screenshots*</em> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please define the screenshot file name (no extension needed) (ex. screenshot_001, {vName})


<dl>
<dt>What to input</dt><dd>Enter file name for the screenshot</dd>
<dt>Sample Data</dt><dd><strong>screenshot_001</strong> or <strong>{vName}</strong></dd>
<dt>Remarks</dt><dd>png image</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserTakeScreenshotCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
