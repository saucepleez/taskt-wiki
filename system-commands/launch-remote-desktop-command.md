<!--TITLE: Launch Remote Desktop Command -->
<!-- SUBTITLE: a command in the System Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


System Commands &gt; Launch Remote Desktop


# Launch Remote Desktop Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Machine Name](#param_0)
- [Please Specify the User Name](#param_1)
- [Please Specify the Password](#param_2)
- [Optional - Please Specify the Width of the RDP Window](#param_3)
- [Optional - Please Specify the Height of the RDP Window](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Specify the Machine Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Machine Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>TOM-PC</strong> or <strong>{vMachine}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>TOM-PC</strong> | Specify **TOM-PC** for Machine Name |
| <strong>{vMachine}</strong> | Specify Value of Variable **vMachine** for Machine Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the User Name


<dl>
<dt>What to input</dt><dd>Enter or Select the User Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>tom</strong> or <strong>{vUser}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>tom</strong> | Specify **tom** for User |
| <strong>{vUser}</strong> | Specify Value of Variable **vUser** for User |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Password


<dl>
<dt>What to input</dt><dd>Enter or Select the Password</dd>
<dt>Sample Usage</dt><dd><strong>mySecretPass</strong> or <strong>{vPass}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>mySecretPass</strong> | Specify **mySecretPass** for Password |
| <strong>{vPass}</strong> | Specify Value of Variable **vPass** for Password |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Width of the RDP Window


<dl>
<dt>What to input</dt><dd>Enter or Select the Width</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>1024</strong> or <strong>{vWidth}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Primary Monitor Size</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1024</strong> | Specify **1024** for Width |
| <strong>{vWidth}</strong> | Specify Value of Variable **vWidth** for Width |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Height of the RDP Window


<dl>
<dt>What to input</dt><dd>Enter or Select the Height</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>768</strong> or <strong>{vHeight}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Primary Monitor Size</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>768</strong> | Specify **768** for Height |
| <strong>{vHeight}</strong> | Specify Value of Variable **vHeight** for Height |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: LaunchRemoteDesktopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
