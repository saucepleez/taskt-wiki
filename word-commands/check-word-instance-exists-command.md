<!--TITLE: Check Word Instance Exists Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Word Instance Exists Command


## What does this command do?
This command returns existance of Word instance.


## When would I want to use this command?
Use this command when you want to check Word instance.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name (ex. myInstance, {vInstance})|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please select the variable to receive the result|Select or provide a variable from the variable list|**vSomeVariable**|Result is **TRUE** or **FALSE**.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: WordCheckWordInstanceExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/21/21 08:44 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
