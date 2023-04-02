<!--TITLE: Set Dictionary Value Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Item &gt; Set Dictionary Value


# Set Dictionary Value Command


## What does this command do?
This command allows you to set value in Dictionary


## When would I want to use this command?
Use this command when you want to set value in Dictionary.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Dictionary Variable Name](#param_0)
- [Please Specify the Name of the Dictionary Key](#param_1)
- [Please Specify the Dictionary Value](#param_2)
- [Optional - Please Select the When Key does not Exists](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Variable Name</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vDictionary</strong> or <strong>{vDictionary}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDictionary</strong> | Specify Variable Name **vDictionary** |
| <strong>{vDictionary}</strong> | Specify Variable Name **vDictionary** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Name of the Dictionary Key


<dl>
<dt>What to input</dt><dd>Enter or Select the Key Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>key1</strong> or <strong>{vKey}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>key1</strong> | Specify **key1** for Dictionary Key |
| <strong>{vKey}</strong> | Specify Value of Variable **vKey** for Dictionary Key |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Dictionary Value


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>1</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** for Dictionary Value |
| <strong>1</strong> | Specify **1** for Dictionary Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Dictionary Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When Key does not Exists


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error</strong> or  <strong>Ignore</strong> or  <strong>Add</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Error</strong> | Rise a Error |
| <strong>Ignore</strong> | Don't Set the Dictionary Item |
| <strong>Add</strong> | Add New Dictionary Item |


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
Automation Class Name: SetDictionaryValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
