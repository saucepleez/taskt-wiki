<!--TITLE: Substring Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; Substring Text


# Substring Text Command


## What does this command do?
This command allows you to trim a Text


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


<a id="param_list"></a>
## Command Parameters
- [Please select a variable or text](#param_0)
- [Please specify Start from Position](#param_1)
- [Optional - Please specify Extract Length (-1 to keep remainder)](#param_2)
- [Please select the variable to receive the Result](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please select a variable or text


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify Start from Position


<dl>
<dt>What to input</dt><dd>Indicate the starting position within the string</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vPosition}</strong></dd>
<dt>Remarks</dt><dd>0 for beginning, 1 for first character, etc.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please specify Extract Length (-1 to keep remainder)


<dl>
<dt>What to input</dt><dd>Indicate if only so many characters should be kept</dd>
<dt>Sample Usage</dt><dd><strong>1</strong> or <strong>-1</strong> or <strong>{vLength}</strong></dd>
<dt>Remarks</dt><dd>-1 to keep remainder, 1 for 1 position after start index.<br><br>
<strong>Optional</strong><br>Default Value is <strong>-1</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please select the variable to receive the Result


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
Automation Class Name: SubstringTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/28/22 09:59 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
