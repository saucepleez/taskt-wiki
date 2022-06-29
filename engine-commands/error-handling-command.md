<!--TITLE: Error Handling Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Error Handling Command


## What does this command do?
This command specifies what to do  after an error is encountered.


## When would I want to use this command?
Use this command when you want to define how your script should behave when an error is encountered.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select an action to take in the event an error occurs|Select the action you want to take when you come across an error.|**Stop Processing** to end the script if an error is encountered or **Continue Processing** to continue running the script|**If Command** allows you to specify and test if a line number encountered an error. In order to use that functionality, you must specify **Continue Processing**|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






## Developer/Additional Reference
Automation Class Name: ErrorHandlingCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/29/22 09:45 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
