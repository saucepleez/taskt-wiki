<!--TITLE: Create Word Application Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Word Commands &gt; Create Word Application


# Create Word Application Command


## What does this command do?
This command creates a Word Application.


## When would I want to use this command?
Use this command when you want to launch a new instance of Word.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Word Instance Name](#param_0)
- [Optional - Please Specify the Comment Field](#param_1)


<a id="param_0"></a>
### Please Select the Word Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Word Instance Name</dd>
<dt>Instance Type</dt><dd>Word</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>RPAWord</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Word</strong> command will cause an error</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPAWord</strong> | Specify **RPAWord** for Word Instance |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for Word Instance |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: WordCreateApplicationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/16/23 05:54 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
