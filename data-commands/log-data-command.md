<!--TITLE: Log Data Command -->
<!-- SUBTITLE: a command in the Data group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Data &gt; Log Data


# Log Data Command


## What does this command do?
This command logs data to files.


## When would I want to use this command?
Use this command when you want to log custom data to a file for debugging or analytical purposes.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Specify the Custom Log Name](#param_0)
- [Please Specify the Text to Log](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Optional - Please Specify the Custom Log Name


<dl>
<dt>What to input</dt><dd>Enter or Select the File Name</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>myLog or {vLogName}</dd>
<dt>Remarks</dt><dd>Date and Time will be automatically appended to the file name. Logs are all saved in 'Documents\taskt\Logs folder'. If 'myLog' is specified, the log file name will be 'taskt <strong>myLog</strong> Logs'.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Engine Logs</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| myLog | Specify myLog |
| {vLogName} | Specify Value of Variable vLogName |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Text to Log


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>Hello or {vLogValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| Hello | Specify Hello |
| {vLogValue} | Specify Value of Variable vLogValue |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: LogDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
