<!--TITLE: Concatenate Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Action &gt; Concatenate Dictionary


# Concatenate Dictionary Command


## What does this command do?
This command allows you to concatenate two Dictionaries.


## When would I want to use this command?
Use this command when you want to concatenate two Dictionaries.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Dictionary1 Variable Name](#param_0)
- [Please Select the Dictionary2 Variable Name](#param_1)
- [Optional - Please Select the When Key already Exists](#param_2)
- [Please Select the New Dictionary Variable Name](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the Dictionary1 Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Variable Name</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vDictionary1</strong> or <strong>{vDictionary1}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDictionary1</strong> | Specify Variable Name **vDictionary1** |
| <strong>{vDictionary1}</strong> | Specify Variable Name **vDictionary1** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Dictionary2 Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Variable Name</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vDictionary2</strong> or <strong>{vDictionary2}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDictionary2</strong> | Specify Variable Name **vDictionary2** |
| <strong>{vDictionary2}</strong> | Specify Variable Name **vDictionary2** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the When Key already Exists


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Overwrite</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Priority on Dictionary 1 |
| <strong>Overwrite</strong> | Priority on Dictionary 2 |
| <strong>Error</strong> | Rise a Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the New Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the New Dictionary Variable Name</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vNewDictionary</strong> or <strong>{vNewDictionary}</strong></dd>
<dt>Remarks</dt><dd>Concatenate Dictionary 1, Dictionary 2 in that order</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vNewDictionary</strong> | Specify Variable Name **vNewDictionary** |
| <strong>{vNewDictionary}</strong> | Specify Variable Name **vNewDictionary** |


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
Automation Class Name: ConcatenateDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
