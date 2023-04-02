<!--TITLE: Math Calculation Command -->
<!-- SUBTITLE: a command in the Numerical Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Numerical Commands &gt; Math Calculation


# Math Calculation Command


## What does this command do?
This command allows you to perform a math calculation and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a math calculation.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Formula to be Computed](#param_0)
- [Optional - Please Specify the Thousand Seperator](#param_1)
- [Optional - Please Specify the Decimal Seperator](#param_2)
- [Please Select the Variable Name to Store Result](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Formula to be Computed


<dl>
<dt>What to input</dt><dd>Enter or Select the Formula to be Computed</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>2+1</strong> or <strong>{vNum}+1</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>2+1</strong> | Specify **2+1** for Formula |
| <strong>{vNum}+1</strong> | Add **1** to the value of Variable **vNum** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Thousand Seperator


<dl>
<dt>What to input</dt><dd>Enter or Select the Thousand Separator</dd>
<dt>Sample Usage</dt><dd><strong>,</strong> or <strong>.</strong> or <strong>{vSeparator}</strong></dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>,</strong> | Specify **comma** for Thousand Separator |
| <strong>.</strong> | Specify **period** for Thousand Separator |
| <strong>{vSeparator}</strong> | Specify Value of Variable **vSeparator** for Thousand Separator |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Decimal Seperator


<dl>
<dt>What to input</dt><dd>Enter or Select the Decimal Separator</dd>
<dt>Sample Usage</dt><dd><strong>,</strong> or <strong>.</strong> or <strong>{vSeparator}</strong></dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<br><br>
<strong>Optional</strong><br>Default Value is <strong>.</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>,</strong> | Specify **comma** for Decimal Seperator |
| <strong>.</strong> | Specify **period** for Decimal Seperator |
| <strong>{vSeparator}</strong> | Specify Value of Variable **vSeparator** for Decimal Seperator |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


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
Automation Class Name: MathCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
