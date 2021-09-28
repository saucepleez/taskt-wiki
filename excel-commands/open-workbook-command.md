<!--TITLE: Open Workbook Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Open Workbook Command


## What does this command do?
This command opens an Excel Workbook.


## When would I want to use this command?
Use this command when you want to open an existing Excel Workbook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error.
If file does not contain extensin, suppliment extensions supported by Excel.
If file does not contain folder path, file will be opened in the same folder as script file.|
|Please indicate the workbook file path|Enter or Select the path to the applicable file that should be opened by Excel.|**C:\temp\myfile.xlsx** or **{vFilePath}**||
|Optional - Please indicate open password|Enter or Select the path to the applicable file that should be opened by Excel.|**myPassword** or **{vPassword}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ExcelOpenWorkbookCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/21 11:00 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
