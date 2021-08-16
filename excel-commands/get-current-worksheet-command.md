<!--TITLE: Get Current Worksheet Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Current Worksheet Command


## What does this command do?
This command allows you to get current sheet name.


## When would I want to use this command?
Use this command when you want to launch a new instance of Excel.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|**myInstance** or **{vInstance}**||
|Please select the variable to receive a sheet name|Select or provide a variable from the variable list|**vSomeVariable**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: ExcelGetCurrentWorksheetCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/16/21 01:36 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)