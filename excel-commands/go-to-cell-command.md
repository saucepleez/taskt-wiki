<!--TITLE: Go To Cell Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Go To Cell Command


## What does this command do?
This command moves to a specific cell.


## When would I want to use this command?
Use this command when you want to move to a new cell from your currently selected cell.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name (ex. myInstance, {vInstance})|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the Cell Location (ex. A1, {vAddress})|Enter the actual location of the cell.|**A1** or **{vAddress}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExcelGoToCellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/21/21 12:05 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
