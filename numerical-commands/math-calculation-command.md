<!--TITLE: Math Calculation Command -->
<!-- SUBTITLE: a command in the Numerical Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Numerical Commands &gt; Math Calculation


# Math Calculation Command


## What does this command do?
This command allows you to perform a math calculation and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a math calculation.


## Command Parameters
- [Please supply the input to be computed](#param_0)
- [Optional - Indicate Thousand Seperator](#param_1)
- [Optional - Indicate Decimal Seperator](#param_2)
- [Please select the variable to receive the math calculation](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please supply the input to be computed


<dl>
<dt>What to input</dt><dd>Specify either text or a variable that contains valid math.</dd>
<dt>Sample Data</dt><dd>2+1 or {vNum}+1</dd>
<dt>Remarks</dt><dd>You can use known numbers or variables.</dd>
</dl>




<a id="param_1"></a>
### Optional - Indicate Thousand Seperator


<dl>
<dt>What to input</dt><dd>Enter the seperator used to identify decimal places</dd>
<dt>Sample Data</dt><dd>, or . or {vSeperator}</dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Optional - Indicate Decimal Seperator


<dl>
<dt>What to input</dt><dd>Enter the seperator used to identify decimal places</dd>
<dt>Sample Data</dt><dd>. or , or {vSeperator}</dd>
<dt>Remarks</dt><dd>Typically a comma or a decimal point (period)<b>Optional</b><br>Default Value is .</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the math calculation


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MathCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
