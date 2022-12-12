<!--TITLE: Stopwatch Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Engine Commands &gt; Stopwatch


# Stopwatch Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


## Command Parameters
- [Please Select the Enter the instance name of the Stopwatch](#param_0)
- [Please Select the Enter the Stopwatch Action](#param_1)
- [Please Specify the Apply Result To Variable](#param_2)
- [Please Specify the Optional - Specify String Format (ex. hh:mm)](#param_3)
- [Please Specify the Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Select the Enter the instance name of the Stopwatch


<dl>
<dt>What to input</dt><dd>Provide a unique instance or way to refer to the stopwatch</dd>
<dt>Instance Type</dt><dd>StopWatch</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select the Enter the Stopwatch Action


<dl>
<dt>What to input</dt><dd>Provide a unique instance or way to refer to the stopwatch</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Start Stopwatch</strong> or  <strong>Stop Stopwatch</strong> or  <strong>Restart Stopwatch</strong> or  <strong>Reset Stopwatch</strong> or  <strong>Measure Stopwatch</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Apply Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Optional - Specify String Format (ex. hh:mm)


<dl>
<dt>What to input</dt><dd>Specify if a specific string format is required.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: StopwatchCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
