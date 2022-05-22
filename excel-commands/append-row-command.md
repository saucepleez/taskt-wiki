<!--TITLE: Append Row Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Append Row Command


## What does this command do?
Append to last row of sheet.


## When would I want to use this command?
Use this command will take in a comma seprerated value and append it to the end of an excel sheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **excelInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the Row to set|Enter the text value that will be set (This could be a DataRow).|Hello,world or {vText}||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: ExcelAppendRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/22/22 08:44 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
