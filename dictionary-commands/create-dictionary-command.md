<!--TITLE: Create Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Action &gt; Create Dictionary


# Create Dictionary Command


## What does this command do?
This command created a DataTable with the column names provided


## When would I want to use this command?
Use this command when you want to create a new Dictionary


<a id="param_list"></a>
## Command Parameters
- [Please Select the Dictionary Variable Name](#param_0)
- [Please Specify the Define Keys and Values](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Variable Name</dd>
<dt>Value</dt><dd>Dictionary Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
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
### Please Specify the Define Keys and Values


<dl>
<dt>What to input</dt><dd>Enter or Select the Keys and Values required for the Dictionary</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <table><thead><tr><th>Keys</th><th>Values</th></tr></thead><tbody><tr><td><strong>Age</strong></td><td><strong>15</strong></td></tr></tbody></table> | Add an item whose key is **Age** and value is **15** |
| <table><thead><tr><th>Keys</th><th>Values</th></tr></thead><tbody><tr><td><strong>Name</strong></td><td><strong>Alice</strong></td></tr></tbody></table> | Add an item whose key is **Name** and value is **Alice** |
| <table><thead><tr><th>Keys</th><th>Values</th></tr></thead><tbody><tr><td><strong>{vKey}</strong></td><td><strong>{vValue}</strong></td></tr></tbody></table> | Add an item whose key is Value of Variable **vKey** and value is Value of Variable **vValue** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: CreateDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
