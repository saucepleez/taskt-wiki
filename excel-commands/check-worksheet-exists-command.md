<!--TITLE: Check Worksheet Exists Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Worksheet Exists Command


## What does this command do?
This command allows you to check existance sheet


## When would I want to use this command?
Use this command when you want to switch to a specific worksheet


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Indicate the name of the sheet within the Workbook to check|Specify the name of the actual sheet|**mySheet**, **Current Sheet**, **{vSheet}**||
|Please select the variable to receive the existance sheet|Select or provide a variable from the variable list|**vSomeVariable**|Result is **TRUE** or **FALSE**|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ExcelCheckWorksheetExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/24/21 02:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
