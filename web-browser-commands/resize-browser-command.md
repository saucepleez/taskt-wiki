<!--TITLE: Resize Browser Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Resize Browser


# Resize Browser Command


## What does this command do?
This command allows you to change browser window size.


## When would I want to use this command?
Use this command when you want to change browser window size.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Optional - Please Specify the Browser Window Width](#param_1)
- [Optional - Please Specify the Browser Window Height](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the WebBrowser Instance Name</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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
### Optional - Please Specify the Browser Window Width


<dl>
<dt>What to input</dt><dd>Enter or Select the Width</dd>
<dt>Sample Usage</dt><dd><strong>640</strong> or <strong>{vWidth}</strong></dd>
<dt>Remarks</dt><dd>Empty means Current Width<br><br>
<strong>Optional</strong><br>Default Value is <strong>Empty and means Current Width</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>640</strong> | Specify **640** for Window Width |
| <strong>{vWidth}</strong> | Specify Value of Variable **vWidth** for Window Width |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Browser Window Height


<dl>
<dt>What to input</dt><dd>Enter or Select the Height</dd>
<dt>Sample Usage</dt><dd><strong>480</strong> or <strong>{vHeight}</strong></dd>
<dt>Remarks</dt><dd>Empty means Current Height<br><br>
<strong>Optional</strong><br>Default Value is <strong>Empty and means Current Height</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>480</strong> | Specify **480** for Window Height |
| <strong>{vHeight}</strong> | Specify Value of Variable **vHeight** for Window Height |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserResizeBrowserCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
