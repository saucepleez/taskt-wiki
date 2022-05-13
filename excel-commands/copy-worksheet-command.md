<!--TITLE: Copy Worksheet Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Copy Worksheet Command


## What does this command do?
This command copy a Excel Worksheet.


## When would I want to use this command?
Use this command when you want to copy a new worksheet to an Excel Instance


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the target worksheet name||**mySheet** or **Current Sheet** or **{vSheet}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Optional - Please Enter the new worksheet name||**newSheet** or **{vNewSheet}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ExcelCopyWorksheetCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/13/22 01:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
