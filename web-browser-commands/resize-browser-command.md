<!--TITLE: Resize Browser Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Resize Browser


# Resize Browser Command


## What does this command do?
This command allows you to change browser window size.


## When would I want to use this command?
Use this command when you want to change browser window size.


## Command Parameters
- [Please Enter the instance name (ex. myInstance, {vInstance})](#param_0)
- [Optional - Please specify Browser window Width (Default is Empty and means current width)](#param_1)
- [Optional - Please specify Browser window Height (Default is Empty and means current width)](#param_2)
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
### Optional - Please specify Browser window Width (Default is Empty and means current width)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>640</strong> or <strong>{vWidth}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify Browser window Height (Default is Empty and means current width)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>480</strong> or <strong>{vHeight}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserResizeBrowser
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
