<!--TITLE: Set Cell Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Cell Command


## What does this command do?
This command sets the value of a cell.


## When would I want to use this command?
Use this command when you want to set a value to a specific cell.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter text to set|Enter the text value that will be set.|**Hello** or **{vText}**||
|Please Enter the Cell Location|Enter the actual location of the cell.|**A1** or **B10** or **{vAddress}**||
|Optional - Value type (Default is Cell)||**Cell** or **Formula** or **Format** or **Color** or **Comment**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ExcelSetCellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/13/21 09:43 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
