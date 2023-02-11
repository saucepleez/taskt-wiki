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
- [Please Specify the Please supply the input to be computed](#param_0)
- [Optional - Please Indicate Thousand Seperator](#param_1)
- [Optional - Please Indicate Decimal Seperator](#param_2)
- [Please select the variable to receive the math calculation](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Please supply the input to be computed


<dl>
<dt>What to input</dt><dd>Specify either text or a variable that contains valid math.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>2+1</strong> or <strong>{vNum}+1</strong></dd>
<dt>Remarks</dt><dd>You can use known numbers or variables.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Indicate Thousand Seperator


<dl>
<dt>What to input</dt><dd>Enter the seperator used to identify decimal places</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Indicate Decimal Seperator


<dl>
<dt>What to input</dt><dd>Enter the seperator used to identify decimal places</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<br><br>
<strong>Optional</strong><br>Default Value is <strong>.</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please select the variable to receive the math calculation


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
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
Automation Class Name: MathCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/11/23 09:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
