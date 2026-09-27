<!--TITLE: Calculate DateTime By Excel Serial Command -->
<!-- SUBTITLE: a command in the DateTime group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime &gt; Calculate &gt; Calculate DateTime By Excel Serial


# Calculate DateTime By Excel Serial Command


## What does this command do?
This command allows you to Calculate DateTime By Excel Serial. Add Day, Minute, etc.


## When would I want to use this command?
Use this command when you want to Calculate DateTime By Excel Serial. Add Day, Minute, etc.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Excel Serial DateTime](#param_0)
- [Please Select the Calculation Method](#param_1)
- [Please Specify the Value to Add or Substruct](#param_2)
- [Please Select the Variable Name to Store Result](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Excel Serial DateTime


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel Serial DateTime</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>43210 or {vSerial}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>43210</strong> | Specify **43210** for Excel Serial. It's means 2018-04-20. |
| <strong>{vSerial}</strong> | Specify Value of Variable **vSerial** for Excel Serial |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Calculation Method


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Add Years</strong> or  <strong>Add Months</strong> or  <strong>Add Days</strong> or  <strong>Add Hours</strong> or  <strong>Add Minutes</strong> or  <strong>Add Seconds</strong> or  <strong>Substract Years</strong> or  <strong>Substract Months</strong> or  <strong>Substract Days</strong> or  <strong>Substract Hours</strong> or  <strong>Substract Minutes</strong> or  <strong>Substract Seconds</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Value to Add or Substruct


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>5 or {vValue}</dd>
<dt>Remarks</dt><dd>Adding <strong>-5</strong> is same as Substructing <strong>5</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>5</strong> | Add or Substruct **5** |
| <strong>{vValue}</strong> | Add or Substruct Value of Variable **vValue** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>DateTime Variable</dd>
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
Automation Class Name: CalculateDateTimeByExcelSerialCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/25/25 10:10 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
