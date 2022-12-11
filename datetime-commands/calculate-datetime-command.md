<!--TITLE: Calculate DateTime Command -->
<!-- SUBTITLE: a command in the DateTime Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime Commands &gt; Calculate DateTime


# Calculate DateTime Command


## What does this command do?
This command allows you to Calculate DateTime. Add Day, Minute, etc.


## When would I want to use this command?
Use this command when you want to Calculate DateTime. Add Day, Minute, etc.


## Command Parameters
- [Please select a DateTime Variable Name](#param_0)
- [Please specify Calculation Method](#param_1)
- [Please specify Value to Add or Substruct](#param_2)
- [Please specify Variable Name to store Result](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please select a DateTime Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>DateTime</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vDateTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify Calculation Method


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Add Years</strong> or  <strong>Add Months</strong> or  <strong>Add Days</strong> or  <strong>Add Hours</strong> or  <strong>Add Minutes</strong> or  <strong>Add Seconds</strong> or  <strong>Substract Years</strong> or  <strong>Substract Months</strong> or  <strong>Substract Days</strong> or  <strong>Substract Hours</strong> or  <strong>Substract Minutes</strong> or  <strong>Substract Seconds</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please specify Value to Add or Substruct


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>5</strong> or <strong>vValue</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify Variable Name to store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CalculateDateTimeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
