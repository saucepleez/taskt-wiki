<!--TITLE: Get Range As Datatable Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Range As Datatable Command


## What does this command do?
This command gets text from a specified Excel Range and put it into a DataTable.


## When would I want to use this command?
Use this command when you want to get a value from a specific range.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **excelInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the First Cell Location (ex. A1 or B2)|Enter the actual location of the cell.|A1, B10, {vAddress}||
|Please select output Option|Indicate whether this command should return a datatable or Delimited String|Select from **Datatable** or **Delimited String**||
|Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)|Enter the actual location of the cell.|A1, B10, {vAddress}||
|Add Headers|When selected, the column headers from the specified spreadsheet range are also extracted.|Select from **Yes** or **No**||
|Assign to Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: ExcelGetRangeCommandAsDT
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/16/21 11:34 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
