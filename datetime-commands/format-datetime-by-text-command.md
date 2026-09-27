<!--TITLE: Format DateTime By Text Command -->
<!-- SUBTITLE: a command in the DateTime group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime &gt; Format &gt; Format DateTime By Text


# Format DateTime By Text Command


## What does this command do?
This command allows you to Format DateTime By Text.


## When would I want to use this command?
Use this command when you want to Format DateTime By Text.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the DateTime Text](#param_0)
- [Please Specify the DateTime Format](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the DateTime Text


<dl>
<dt>What to input</dt><dd>Enter or Select the DateTime Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>2000-01-01 or {vText}}</dd>
<dt>Remarks</dt><dd>Recommended to Disable the Auto Calculation</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>2000-01-01</strong> | Specify **2000-01-01** for DateTime |
| <strong>{vText}}</strong> | Specify Value of Variable **vText** for DateTime |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the DateTime Format


<dl>
<dt>What to input</dt><dd>Enter or Select the DateTime Format Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>MM/dd/yyyy or HH:mm:ss or {vFormat}</dd>
<dt>Remarks</dt><dd>Please refer to the Microsoft DateTime.ToString() page for format details</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>MM/dd/yyyy</strong> | Specify Format Month/Day/Year |
| <strong>HH:mm:ss</strong> | Specify Format Hour/Minute/Second |
| {vFormat} | Specify Value of Variable vFormat for Format |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
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
Automation Class Name: FormatDateTimeByTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
