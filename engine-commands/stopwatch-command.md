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
- [Enter the instance name of the Stopwatch](#param_0)
- [Enter the Stopwatch Action](#param_1)
- [Apply Result To Variable](#param_2)
- [Optional - Specify String Format (ex. hh:mm)](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Enter the instance name of the Stopwatch


<dl>
<dt>What to input</dt><dd>Provide a unique instance or way to refer to the stopwatch</dd>
<dt>Instance Type</dt><dd>StopWatch</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Sample Data</dt><dd><strong>myStopwatch</strong>, <strong>{vStopWatch}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Enter the Stopwatch Action


<dl>
<dt>What to input</dt><dd>Provide a unique instance or way to refer to the stopwatch</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Start Stopwatch</strong> or  <strong>Stop Stopwatch</strong> or  <strong>Restart Stopwatch</strong> or  <strong>Reset Stopwatch</strong> or  <strong>Measure Stopwatch</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Apply Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Optional - Specify String Format (ex. hh:mm)


<dl>
<dt>What to input</dt><dd>Specify if a specific string format is required.</dd>
<dt>Sample Data</dt><dd>MM/dd/yy, hh:mm, etc.</dd>
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
Automation Class Name: StopwatchCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
