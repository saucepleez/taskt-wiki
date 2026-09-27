<!--TITLE: Create JSON Variable Command -->
<!-- SUBTITLE: a command in the JSON group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON &gt; Action &gt; Create JSON Variable


# Create JSON Variable Command


## What does this command do?
This command allows you to create JSON Variable.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the JSON Variable Name](#param_0)
- [Please Specify the JSON Value](#param_1)
- [Optional - Please Select the Value Type to Add](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the JSON Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON <strong>Variable Name</strong></dd>
<dt>Value</dt><dd>JSON Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vJSON or {vJSON}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vJSON</strong> | Specify Variable Name **vJSON** |
| <strong>{vJSON}</strong> | Specify Variable Name **vJSON** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the JSON Value


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON Value</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>Hello or 1 or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Add Text **Hello** |
| <strong>1</strong> | Add Number **Hello** |
| <strong>{vValue}</strong> | Add Value of Variable **vValue** |
| <strong>{ &quot;id&quot;: 1, &quot;value&quot;: &quot;Hello&quot; }</strong> | Add JSON Object |
| <strong>[ 1, 2, &quot;Hello&quot; ]</strong> | Add JSON Array |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Value Type to Add


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>Object</strong> or  <strong>Array</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Auto</strong> | Automatically determines the Value Type |
| <strong>Object</strong> | Specify JSON Object for Value Type |
| <strong>Array</strong> | Specify Array Object for Value Type |


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
Automation Class Name: CreateJSONVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
