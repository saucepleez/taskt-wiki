<!--TITLE: Set NLG Parameter Command -->
<!-- SUBTITLE: a command in the NLG Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


NLG Commands &gt; Set NLG Parameter


# Set NLG Parameter Command


## What does this command do?
This command allows you to define a NLG parameter


## When would I want to use this command?
Use this command when you want to define NLG parameters


<a id="param_list"></a>
## Command Parameters
- [Please Select the NLG Instance Name](#param_0)
- [Please Select the NLG Parameter Type](#param_1)
- [Please Specify the Parameter Value](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the NLG Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the NLG Instance Name</dd>
<dt>Instance Type</dt><dd>NLG</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>nlgInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create NLG Instance</strong> command will cause an error</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>nlgInstance</strong> | Specify **nlgInstance** for Instance |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for Instance |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the NLG Parameter Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Set Subject</strong> or  <strong>Set Verb</strong> or  <strong>Set Object</strong> or  <strong>Add Complement</strong> or  <strong>Add Modifier</strong> or  <strong>Add Pre-Modifier</strong> or  <strong>Add Front Modifier</strong> or  <strong>Add Post Modifier</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Parameter Value


<dl>
<dt>What to input</dt><dd>Parameter Value</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




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
Automation Class Name: NLGSetNLGParameterCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/24/23 06:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
