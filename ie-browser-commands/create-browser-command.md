<!--TITLE: Create Browser Command -->
<!-- SUBTITLE: a command in the IE Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
IE Browser Commands &gt; Create Browser


# Create Browser Command


## What does this command do?
This command allows you to create a new IE web browser session.


## When would I want to use this command?



## Command Parameters
- [Please Enter the instance name](#param_0)
- [Instance Tracking (after task ends)](#param_1)
- [Please Enter the URL to navigate to](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Instance Tracking (after task ends)


<dl>
<dt>What to input</dt><dd>Specify if taskt should remember this instance name after the script has finished executing.</dd>
<dt>Sample Data</dt><dd>Select Forget Instance to forget the instance or Keep Instance Alive to allow subsequent tasks to call the instance by name.</dd>
<dt>Remarks</dt><dd>Calling the Close Browser command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.</dd>
</dl>




<a id="param_2"></a>
### Please Enter the URL to navigate to


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: IEBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
