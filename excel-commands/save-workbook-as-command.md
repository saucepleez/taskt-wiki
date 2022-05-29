<!--TITLE: Save Workbook As Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Save Workbook As Command


## What does this command do?
This command allows you to save an Excel workbook.


## When would I want to use this command?
Use this command when you want to save a workbook to a file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error.|
|Please indicate the directory of the file|Enter or Select the path to the file.|**C:\temp\myfile.xlsx** or **{vExcelFilePath}**|If file does not contain extensin, supplement xlsx extension.<br>If file does not contain folder path, file will be saved in the same folder as script file.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: ExcelSaveAsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/29/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
