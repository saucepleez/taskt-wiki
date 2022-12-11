<!--TITLE: Loop List Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Loop Commands &gt; Loop List


# Loop List Command


## What does this command do?
This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to iterate over each item in a list, or a series of items.


## Command Parameters
- [Please input the list variable to be looped (ex. {vList}, [1,2,3])](#param_0)
- [Comment Field (Optional)](#param_1)


<a id="param_0"></a>
### Please input the list variable to be looped (ex. {vList}, [1,2,3])


<dl>
<dt>What to input</dt><dd>Enter a variable which contains a list of items</dd>
<dt>Sample Data</dt><dd><strong>{vMyList}</strong> or <strong>[1,2,3]</strong></dd>
<dt>Remarks</dt><dd>Use this command to iterate over the results of the Split command.</dd>
</dl>




<a id="param_1"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: BeginListLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
