<!--TITLE: Ping Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Misc Commands &gt; Network/Internet &gt; Ping


# Ping Command


## What does this command do?
This command allows you to add an in-line comment to the script.


## When would I want to use this command?
Use this command when you want to add code comments or document code.  Usage of variables (ex. [vVar]) within the comment block will be parsed and displayed when running the script.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the IP Address or Host Name that you want to ping (ex. 192.168.0.1, {vHost})](#param_0)
- [Please Select the Variable Name to Store Result](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Specify the IP Address or Host Name that you want to ping (ex. 192.168.0.1, {vHost})


<dl>
<dt>What to input</dt><dd>Enter or Select the IP Address or Host Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>192.168.0.1</strong> or <strong>http://example.com</strong> or <strong>{vHost}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>192.168.0.1</strong> | Specify **192.168.0.1** for IP Address |
| <strong>http://example.com</strong> | Specify **http://example.com** for Host Name |
| <strong>{vHost}</strong> | Specify Value of Variable **vHost** for IP or Host |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>The result is PingRelay class converted to JSON format.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: PingCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)