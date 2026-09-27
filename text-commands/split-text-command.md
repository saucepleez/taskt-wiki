<!--TITLE: Split Text Command -->
<!-- SUBTITLE: a command in the Text group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text &gt; Action &gt; Split Text


# Split Text Command


## What does this command do?
This command allows you to split a Text


## When would I want to use this command?
Use this command when you want to split a single Text or variable into multiple items


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Text Value](#param_0)
- [Please Specify the Delimiter](#param_1)
- [Please Select the Variable Name to Store List](#param_2)
- [Optional - Please Select the Remove Empty Item](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Text Value


<dl>
<dt>What to input</dt><dd>Enter or Select the Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or Hello or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify **1** for Text Value |
| <strong>Hello</strong> | Specify **Hello** for Text Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Text Value |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Delimiter


<dl>
<dt>What to input</dt><dd>Enter or Select the Delimiter</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>, or {Char.NewLine} or {TextSplit.Charactor} or {vChar}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>,</strong> | Specify **,** for Delimiter |
| <strong>{Char.NewLine}</strong> | Specify **Line Break** for Delimiter |
| <strong>{TextSplit.Charactor}</strong> | Split by one character |
| <strong>{vChar}</strong> | Specify Value of Variable **vChar** for Delimiter |
| <strong>{Char.Space}</strong> | Split by **Space**. Please specify **Disable Auto Calculation** before this command. |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store List


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vList or {vList}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vList</strong> | Specify Variable Name **vList** |
| <strong>{vList}</strong> | Specify Variable Name **vList** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Remove Empty Item


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
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
Automation Class Name: SplitTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
