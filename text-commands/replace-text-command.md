<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; Replace Text


# Replace Text Command


## What does this command do?
This command allows you to replace text


## When would I want to use this command?
Use this command when you want to replace existing text within text or a variable with new text


<a id="param_list"></a>
## Command Parameters
- [Please select text or variable to modify](#param_0)
- [Please Indicate the text to be replaced](#param_1)
- [Optional - Please Indicate the replacement value](#param_2)
- [Please select the variable to receive the changes](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please select text or variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Indicate the text to be replaced


<dl>
<dt>What to input</dt><dd>Enter the old value of the text that will be replaced</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>H</strong> or <strong>{vTextA}</strong></dd>
<dt>Remarks</dt><dd>H in Hello would be targeted for replacement</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Indicate the replacement value


<dl>
<dt>What to input</dt><dd>Enter the new value after replacement</dd>
<dt>Sample Usage</dt><dd><strong>J</strong>, <strong>{vTextB}</strong></dd>
<dt>Remarks</dt><dd>H would be replaced with J to create 'Jello'<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please select the variable to receive the changes


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




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
Automation Class Name: ReplaceTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/04/23 01:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
