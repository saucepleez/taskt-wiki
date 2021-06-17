<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Replace Text Command


## What does this command do?
This command allows you to replace text in a Word document.


## When would I want to use this command?
Use this command when you want to replace text in a document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please define the text to find|Enter the text you wish to find.|**findText**||
|Please define the text to replace with|Enter the text you wish to replace the found text.|**replaceWithText**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: WordReplaceTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/17/21 09:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
