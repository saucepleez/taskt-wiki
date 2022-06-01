<!--TITLE: Get Last Row Index Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Last Row Index Command


## What does this command do?
This command allows you to find the last row in a used range in an Excel Workbook.


## When would I want to use this command?
Use this command to determine how many rows have been used in the Excel Workbook.  You can use this value in a **Number Of Times** Loop to get data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Optional - Please Enter Letter of the Column to check (Default is A)|Enter a valid column letter|**A** or **B** or **{vColumn}**||
|Please select the variable to receive the row number|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ExcelGetLastRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/22 11:50 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
