<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Word Commands &gt; Replace Text


# Replace Text Command


## What does this command do?
This command allows you to replace text in a Word document.


## When would I want to use this command?
Use this command when you want to replace text in a document.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Word Instance Name](#param_0)
- [Please Specify the Text to Find](#param_1)
- [Optional - Please Specify the Text to Replace with](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the Word Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Word Instance Name</dd>
<dt>Instance Type</dt><dd>Word</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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
### Please Specify the Text to Find


<dl>
<dt>What to input</dt><dd>Enter or Select the Text to Find</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** for Text to Find |
| <strong>{vText}</strong> | Specify Value of Variable **vText** for Text to Find |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Text to Replace with


<dl>
<dt>What to input</dt><dd>Enter or Select the Text to Replace with</dd>
<dt>Sample Usage</dt><dd><strong>Hi!</strong> or <strong>{vNewText}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hi!</strong> | Specify **Hi!** for Text to Replace with |
| <strong>{vNewText}</strong> | Specify Value of Variable **vNewText** for Text to Replace with |


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
Automation Class Name: WordReplaceTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
