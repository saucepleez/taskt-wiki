<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Word Commands &gt; Replace Text


# Replace Text Command


## What does this command do?
This command allows you to replace text in a Word document.


## When would I want to use this command?
Use this command when you want to replace text in a document.


## Command Parameters
- [Please enter the instance name](#param_0)
- [Please define the text to find](#param_1)
- [Please define the text to replace with](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Word command</dd>
<dt>Sample Data</dt><dd>myInstance or wordInstance</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Word command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please define the text to find


<dl>
<dt>What to input</dt><dd>Enter the text you wish to find.</dd>
<dt>Sample Data</dt><dd>findText</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please define the text to replace with


<dl>
<dt>What to input</dt><dd>Enter the text you wish to replace the found text.</dd>
<dt>Sample Data</dt><dd>replaceWithText</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WordReplaceTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
