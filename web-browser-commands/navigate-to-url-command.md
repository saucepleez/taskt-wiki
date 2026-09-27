<!--TITLE: Navigate To URL Command -->
<!-- SUBTITLE: a command in the Web Browser group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser &gt; Navigate &gt; Navigate To URL


# Navigate To URL Command


## What does this command do?
This command allows you to navigate a Selenium web browser session to a given URL or resource.


## When would I want to use this command?
Use this command when you want to navigate an existing Selenium instance to a known URL or web resource


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Please Specify the URL to navigate to](#param_1)
- [Optional - Please Select the HTTPS usage](#param_2)
- [Optional - Please Select the When Fail Action](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Value</dt><dd>WebBrowser Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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
### Please Specify the URL to navigate to


<dl>
<dt>What to input</dt><dd>Enter or Select the URL</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>https://mycompany.com/orders or {vURL}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>https://mycompany.com/orders</strong> | Specify **https://mycompany.com/orders** for URL |
| <strong>{vURL}</strong> | Specify Value of Variable **vURL** for URL |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the HTTPS usage


<dl>
<dt>What to input</dt><dd>Please specify <strong>True</strong> or <strong>False</strong></dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>True</strong> or  <strong>False</strong></dd>
<dt>Remarks</dt><dd>Choose if you want to use HTTP or HTTPS for navigation. If no protocol is specified in the URL above, taskt will resort to this choice.<br><br>
<strong>Optional</strong><br>Default Value is <strong>True</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>True</strong> | Use **HTTPS** when no protocol is specified in the URL |
| <strong>False</strong> | Use **HTTP** when no protocol is specified in the URL |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When Fail Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing To Do |
| <strong>Error</strong> | Rise an Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserNavigateToURLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
