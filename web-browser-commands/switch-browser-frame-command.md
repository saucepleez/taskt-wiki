<!--TITLE: Switch Browser Frame Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Web Browser Commands &gt; Actions &gt; Switch Browser Frame


# Switch Browser Frame Command


## What does this command do?
This command allows you to create a new Selenium web browser session which enables automation for websites.


## When would I want to use this command?
Use this command when you want to create a browser that will eventually perform web automation such as checking an internal company intranet site to retrieve data


## Command Parameters
- [Please Enter the instance name (ex. myInstance , {vInstance})](#param_0)
- [Indicate Frame Selection Type](#param_1)
- [Optional - Frame Search Parameter (If Selection Type is 'Index' or 'Name of ID', please enter)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstance , {vInstance})


<dl>
<dt>What to input</dt><dd>Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Browser command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Indicate Frame Selection Type


<dl>
<dt>What to input</dt><dd>Select an option which best fits to the specification you would like to make.</dd>
<dt>Sample Data</dt><dd>Select one of the provided options.</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Frame Search Parameter (If Selection Type is 'Index' or 'Name of ID', please enter)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>Index: 0 or {vIndex}, Name/ID: top or {vName}</dd>
<dt>Remarks</dt><dd>If selection type is 'Index', default index is 0.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserSwitchFrameCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
