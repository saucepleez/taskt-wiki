<!--TITLE: Loop Number Of Times Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Loop Commands &gt; Loop Number Of Times


# Loop Number Of Times Command


## What does this command do?
This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to perform a series of commands a specified amount of times.


## Command Parameters
- [Enter how many times to perform the loop (ex. 5, {vNum})](#param_0)
- [Optional - Define Start Index (Default: 0)](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Enter how many times to perform the loop (ex. 5, {vNum})


<dl>
<dt>What to input</dt><dd>Enter the amount of times you would like to perform the encased commands.</dd>
<dt>Sample Data</dt><dd>5 or 10 or {vNum}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Define Start Index (Default: 0)


<dl>
<dt>What to input</dt><dd>Enter the starting index of the loop.</dd>
<dt>Sample Data</dt><dd>0 or 1 or {vStartValue}</dd>
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
Automation Class Name: BeginNumberOfTimesLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
