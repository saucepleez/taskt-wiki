<!--TITLE: Date Calculation Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Data Commands &gt; Date Calculation


# Date Calculation Command


## What does this command do?
This command allows you to build a date and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a date calculation.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Please supply the date value or variable](#param_0)
- [Please Select a Calculation Method](#param_1)
- [Please Specify the Please supply the increment value](#param_2)
- [Optional - Please Specify String Format](#param_3)
- [Please select the variable to receive the date calculation](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Specify the Please supply the date value or variable


<dl>
<dt>What to input</dt><dd>Specify either text or a variable that contains the start date.</dd>
<dt>Sample Usage</dt><dd><strong>{DateTime.Now}</strong> or <strong>1/1/2000</strong></dd>
<dt>Remarks</dt><dd>You can use known text or variables.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select a Calculation Method


<dl>
<dt>What to input</dt><dd>Select the necessary operation</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Add Seconds</strong> or  <strong>Add Minutes</strong> or  <strong>Add Hours</strong> or  <strong>Add Days</strong> or  <strong>Add Years</strong> or  <strong>Subtract Seconds</strong> or  <strong>Subtract Minutes</strong> or  <strong>Subtract Hours</strong> or  <strong>Subtract Days</strong> or  <strong>Subtract Years</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Please supply the increment value


<dl>
<dt>What to input</dt><dd>Enter how many units to increment by</dd>
<dt>Sample Usage</dt><dd>15, {vIncrement}</dd>
<dt>Remarks</dt><dd>You can use negative numbers which will do the opposite, ex. Subtract Days and an increment of -5 will Add Days.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify String Format


<dl>
<dt>What to input</dt><dd>Specify if a specific string format is required.</dd>
<dt>Sample Usage</dt><dd><strong>MM/dd/yy</strong> or <strong>hh:mm</strong> or etc.</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please select the variable to receive the date calculation


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




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
Automation Class Name: DateCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
