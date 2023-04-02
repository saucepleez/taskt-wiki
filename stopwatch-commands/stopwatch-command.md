<!--TITLE: StopWatch Command -->
<!-- SUBTITLE: a command in the StopWatch Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


StopWatch Commands &gt; StopWatch


# StopWatch Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Stopwatch Instance Name](#param_0)
- [Please Select the Stopwatch Action](#param_1)
- [Optional - Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the DateTime Format](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the Stopwatch Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the StopWatch Instance Name</dd>
<dt>Instance Type</dt><dd>StopWatch</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>myStopWatch</strong> | Specify **myStopWatch** for StopWatch Instance |
| <strong>{vStopWatch}</strong> | Specify Value of Variable **vStopWatch** for StopWatch Instance |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Stopwatch Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Start Stopwatch</strong> or  <strong>Stop Stopwatch</strong> or  <strong>Restart Stopwatch</strong> or  <strong>Reset Stopwatch</strong> or  <strong>Measure Stopwatch</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
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
### Optional - Please Specify the DateTime Format


<dl>
<dt>What to input</dt><dd>Enter or Select the DateTime Format</dd>
<dt>Sample Usage</dt><dd><strong>MM/dd/yy</strong> or <strong>hh:mm</strong> or <strong>{vFormat}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>MM/dd/yy</strong> | Specify **MM/dd/yy** for DateTime Format. It is **Strongly Recommended** to **Disable Automatic Calculation** when using this format |
| <strong>hh:mm</strong> | Specify **hh:mm** for Format |
| <strong>{vFormat}</strong> | Specify Value of Variable **vFormat** for Format |


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
Automation Class Name: StopwatchCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
