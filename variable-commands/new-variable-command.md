<!--TITLE: New Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Variable Commands &gt; New Variable


# New Variable Command


## What does this command do?
This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Variable Name](#param_0)
- [Optional - Please Specify the Variable Value](#param_1)
- [Optional - Please Select the When the Variable Already Exists](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vSomeVariable or {vSomeVariable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vSomeVariable</strong> | Specify **vSomeVariable** for Variable Name |
| <strong>{vSomeVariable}</strong> | Specify **vSomeVariable** for the Variable Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Variable Value


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Value</dd>
<dt>Sample Usage</dt><dd>Hello or {vNum}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Specify **Hello** for Variable Value |
| <strong>{vNum}</strong> | Specify Value of Variable **vNum** for Variable Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the When the Variable Already Exists


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Do Nothing If Variable Exists</strong> or  <strong>Error If Variable Exists</strong> or  <strong>Replace If Variable Exists</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Replace If Variable Exists</strong></dd>
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
Automation Class Name: NewVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
