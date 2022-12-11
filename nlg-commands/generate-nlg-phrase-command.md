<!--TITLE: Generate NLG Phrase Command -->
<!-- SUBTITLE: a command in the NLG Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


NLG Commands &gt; Generate NLG Phrase


# Generate NLG Phrase Command


## What does this command do?
This command pauses the script for a set amount of time specified in milliseconds.


## When would I want to use this command?
Use this command when you want to pause your script for a specific amount of time.  After the specified time is finished, the script will resume execution.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Select Variable to Receive Output](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create NLG Instance</strong> command</dd>
<dt>Instance Type</dt><dd>NLG</dd>
<dt>Sample Data</dt><dd><strong>nlgDefaultInstance</strong> or <strong>myInstance</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create NLG Instance</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Select Variable to Receive Output


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
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
Automation Class Name: NLGGeneratePhraseCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
