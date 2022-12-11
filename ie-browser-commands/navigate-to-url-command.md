<!--TITLE: Navigate to URL Command -->
<!-- SUBTITLE: a command in the IE Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


IE Browser Commands &gt; Navigate to URL


# Navigate to URL Command


## What does this command do?
This command allows you to navigate a IE web browser session to a given URL or resource.


## When would I want to use this command?
Use this command when you want to navigate an existing IE instance to a known URL or web resource


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the URL to navigate to](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create IE Browser</strong> command</dd>
<dt>Instance Type</dt><dd>IE</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>IEInstance</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create IE Browser</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the URL to navigate to


<dl>
<dt>What to input</dt><dd>Enter the destination URL that you want the IE instance to navigate to</dd>
<dt>Sample Data</dt><dd>https://mycompany.com/orders</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: IEBrowserNavigateURLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
