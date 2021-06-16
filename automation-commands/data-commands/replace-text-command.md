<!--TITLE: Replace Text Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Replace Text Command


## What does this command do?
This command allows you to replace text


## When would I want to use this command?
Use this command when you want to replace existing text within text or a variable with new text


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select text or variable to modify|Select or provide a variable from the variable list|**vSomeVariable**||
|Indicate the text to be replaced|Enter the old value of the text that will be replaced|H|H in Hello would be targeted for replacement|
|Indicate the replacement value|Enter the new value after replacement|J|H would be replaced with J to create 'Jello'|
|Please select the variable to receive the changes|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: StringReplaceCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
