<!--TITLE: Get Last Index Of Command -->
<!-- SUBTITLE: a command in the Text group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text &gt; Check/Get &gt; Get Last Index Of


# Get Last Index Of Command


## What does this command do?
This command allows you to the Last Position of the Specified Text


## When would I want to use this command?
Use this command when you want to the Last Position of the Specified Text


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Text Value](#param_0)
- [Please Specify the Search Text](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Select the Case Sensitive](#param_3)
- [Optional - Please Specify the Search Start Position](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Specify the Text Value


<dl>
<dt>What to input</dt><dd>Enter or Select the Text Value</dd>
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
### Please Specify the Search Text


<dl>
<dt>What to input</dt><dd>Enter or Select the Search Text</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>Hello or {vSearch}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** for Search Text |
| <strong>{vSearch}</strong> | Specify Value of Variable **vSearch** for Search Text |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Case Sensitive


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Yes</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Yes</strong> | Comparison Method is Case Sensitive |
| <strong>No</strong> | Comparison Method is NOT Case Sensitive |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Search Start Position


<dl>
<dt>What to input</dt><dd>Search Start Position</dd>
<dt>Sample Usage</dt><dd>0 or -1 or {vPos}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>-1</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify First Charactor Position |
| <strong>-1</strong> | Specify Last Charactor Position |
| <strong>{vPos}</strong> | Specify Value of Variable **vPos** for Search Start Position |


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
Automation Class Name: TextGetLastIndexOfCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/23/25 08:15 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
