<!--TITLE: Navigate to URL Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Navigate &gt; Navigate to URL


# Navigate to URL Command


## What does this command do?
This command allows you to navigate a Selenium web browser session to a given URL or resource.


## When would I want to use this command?
Use this command when you want to navigate an existing Selenium instance to a known URL or web resource


## Command Parameters
- [Please Enter the instance name (ex. myInstacne, {vInstance})](#param_0)
- [Please Enter the URL to navigate to (ex. https://mycompany.com/orders, {vURL})](#param_1)
- [Optional - Specify HTTPS usage](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstacne, {vInstance})


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Browser</strong> command</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the URL to navigate to (ex. https://mycompany.com/orders, {vURL})


<dl>
<dt>What to input</dt><dd>Enter the destination URL that you want the selenium instance to navigate to</dd>
<dt>Sample Data</dt><dd><strong>https://mycompany.com/orders</strong> or <strong>{vURL}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Specify HTTPS usage


<dl>
<dt>What to input</dt><dd>Choose if you want to use HTTP or HTTPS for navigation. If no protocol is specified in the URL above, taskt will resort to this choice.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>&quot;True&quot; to use HTTPS, &quot;False&quot; if you want to try HTTP instead</dd>
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
Automation Class Name: SeleniumBrowserNavigateURLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
