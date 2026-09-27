<!--TITLE: Slice List Command -->
<!-- SUBTITLE: a command in the List group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List &gt; List Actions &gt; Slice List


# Slice List Command


## What does this command do?
This command allows you to Get a Part of the List.


## When would I want to use this command?
Use this command when you want to Get a Part of the List.


<a id="param_list"></a>
## Command Parameters
- [Please Select the List Variable Name](#param_0)
- [Please Select the Slice Method](#param_1)
- [Optional - Please Specify the List Index 1](#param_2)
- [Optional - Please Specify the List Index 2](#param_3)
- [Please Select the New List Variable Name](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Select the List Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Slice Method


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Range</strong> or  <strong>From First To Nth</strong> or  <strong>After Nth From First</strong> or  <strong>From Last To Nth</strong> or  <strong>Before Nth From Last</strong> or  <strong>Odd Numbered Items</strong> or  <strong>Even Numbered Items</strong> or  <strong>Custom Print Like Specifications</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the List Index 1


<dl>
<dt>What to input</dt><dd>Enter or Select the Index of the List</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify First List Item |
| <strong>-1</strong> | Specify Last List Item |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the List Index 2


<dl>
<dt>What to input</dt><dd>Enter or Select the Index of the List</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify First List Item |
| <strong>-1</strong> | Specify Last List Item |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Select the New List Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Value</dt><dd>List Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vNewList or {vNewList}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vNewList</strong> | Specify Variable Name **vNewList** |
| <strong>{vNewList}</strong> | Specify Variable Name **vNewList** |


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
Automation Class Name: SliceListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
