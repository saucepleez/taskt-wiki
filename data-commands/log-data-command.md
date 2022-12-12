<!--TITLE: Log Data Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Data Commands &gt; Log Data


# Log Data Command


## What does this command do?
This command logs data to files.


## When would I want to use this command?
Use this command when you want to log custom data to a file for debugging or analytical purposes.


## Command Parameters
- [Please Select the Select existing log file or enter a custom name.(ex. MyLog, Engine Log)](#param_0)
- [Please enter the text to log.](#param_1)
- [Please Specify the Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Select the Select existing log file or enter a custom name.(ex. MyLog, Engine Log)


<dl>
<dt>What to input</dt><dd>Indicate the file name where logs should be appended to</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Engine Logs</strong></dd>
<dt>Remarks</dt><dd>Date and Time will be automatically appended to the file name.  Logs are all saved in taskt Root\Logs folder</dd>
</dl>




<a id="param_1"></a>
### Please enter the text to log.


<dl>
<dt>What to input</dt><dd>Indicate the value of the text to be saved.</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: LogDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
