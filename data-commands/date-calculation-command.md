<!--TITLE: Date Calculation Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Data Commands &gt; Date Calculation


# Date Calculation Command


## What does this command do?
This command allows you to build a date and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a date calculation.


## Command Parameters
- [Please supply the date value or variable](#param_0)
- [Please Select a Calculation Method](#param_1)
- [Please supply the increment value](#param_2)
- [Optional - Specify String Format](#param_3)
- [Please select the variable to receive the date calculation](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please supply the date value or variable


<dl>
<dt>What to input</dt><dd>Specify either text or a variable that contains the start date.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>{DateTime.Now}</strong> or <strong>1/1/2000</strong></dd>
<dt>Remarks</dt><dd>You can use known text or variables.</dd>
</dl>




<a id="param_1"></a>
### Please Select a Calculation Method


<dl>
<dt>What to input</dt><dd>Select the necessary operation</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select From Add Seconds, Add Minutes, Add Hours, Add Days, Add Years, Subtract Seconds, Subtract Minutes, Subtract Hours, Subtract Days, Subtract Years</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please supply the increment value


<dl>
<dt>What to input</dt><dd>Enter how many units to increment by</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>15, {vIncrement}</dd>
<dt>Remarks</dt><dd>You can use negative numbers which will do the opposite, ex. Subtract Days and an increment of -5 will Add Days.</dd>
</dl>




<a id="param_3"></a>
### Optional - Specify String Format


<dl>
<dt>What to input</dt><dd>Specify if a specific string format is required.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>MM/dd/yy</strong> or <strong>hh:mm</strong> or etc.</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Please select the variable to receive the date calculation


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: DateCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
