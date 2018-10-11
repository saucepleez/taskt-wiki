<!--TITLE: Get Last Row Command -->
<!-- SUBTITLE: a command in the Excel Commands group -->
# Get Last Row Command


## What does this command do?
This command allows you to find the last row in a used range in an Excel Workbook.


## When would I want to use this command?
Use this command to determine how many rows have been used in the Excel Workbook.  You can use this value in a **Number Of Times** Loop to get data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **seleniumInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter Letter of the Column to check (ex. A, B, C)|Enter a valid column letter|A, B, AA, etc.||
|Please select the variable to receive the row number|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExcelGetLastRowCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:04 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
