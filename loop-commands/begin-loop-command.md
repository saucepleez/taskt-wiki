<!--TITLE: Begin Loop Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Loop Commands &gt; Begin Loop


# Begin Loop Command


## What does this command do?
This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false


## When would I want to use this command?
Use this command when you want to check if a statement is 'true' or 'false' and subsequently loop actions based on either condition. Any 'BeginLoop' command must have a following 'EndLoop' command.


## Command Parameters
- [Please select type of Loop Command](#param_0)
- [Additional Parameters](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please select type of Loop Command


<dl>
<dt>What to input</dt><dd>Select the necessary comparison type.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Value</strong>, <strong>Window Name Exists</strong>, <strong>Active Window Name Is</strong>, <strong>File Exists</strong>, <strong>Folder Exists</strong>, <strong>Web Element Exists</strong>, <strong>Error Occured</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Additional Parameters


<dl>
<dt>What to input</dt><dd>Select the required comparison parameters.</dd>
<dt>Sample Data</dt><dd>n/a</dd>
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
Automation Class Name: BeginLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
