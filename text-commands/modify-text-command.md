<!--TITLE: Modify Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; Modify Text


# Modify Text Command


## What does this command do?
This command allows you to trim Text, convert Text, etc.


## When would I want to use this command?
Use this command when you want to trim Text, convert Text, etc.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Please Supply the Text or Variable to modify](#param_0)
- [Please Select Modify Method](#param_1)
- [Please select the variable to receive the changes](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the Please Supply the Text or Variable to modify


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select Modify Method


<dl>
<dt>What to input</dt><dd>Indicate if only so many characters should be kept</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>To Upper Case</strong> or  <strong>To Lower Case</strong> or  <strong>To Base64 String</strong> or  <strong>From Base64 String</strong> or  <strong>Trim</strong> or  <strong>Trim Start</strong> or  <strong>Trim End</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
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
Automation Class Name: ModifyTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/05/23 07:08 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
