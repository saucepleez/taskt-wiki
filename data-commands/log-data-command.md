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
- [Select existing log file or enter a custom name.(ex. MyLog, Engine Log)](#param_0)
- [Please enter the text to log.](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Select existing log file or enter a custom name.(ex. MyLog, Engine Log)


<dl>
<dt>What to input</dt><dd>Indicate the file name where logs should be appended to</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select 'Engine Logs' or specify your own file</dd>
<dt>Remarks</dt><dd>Date and Time will be automatically appended to the file name.  Logs are all saved in taskt Root\Logs folder</dd>
</dl>




<a id="param_1"></a>
### Please enter the text to log.


<dl>
<dt>What to input</dt><dd>Indicate the value of the text to be saved.</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Data</dt><dd>Third Step Complete, {vVariable}, etc.</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: LogDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
