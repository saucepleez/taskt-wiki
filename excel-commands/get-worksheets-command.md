<!--TITLE: Get Worksheets Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Worksheets Command


## What does this command do?
This command allows you to get a specific worksheet names


## When would I want to use this command?
Use this command when you want to switch to a specific worksheet


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Optional - Indicate the name of the sheet to search (Default is empty, and get all sheets)|Specify the name of the actual sheet|**mySheet** or **Current Sheet** or **{vSheet}**||
|Optional - Specify search method (Default is Contains)||**Contains** or **Start with** or **End with**||
|Please select the variable to receive sheet names|Select or provide a variable from the variable list|**vSomeVariable**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ExcelGetWorksheetsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/04/21 10:21 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
