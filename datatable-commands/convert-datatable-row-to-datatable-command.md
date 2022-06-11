<!--TITLE: Convert DataTable Row To DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Convert DataTable Row To DataTable Command


## What does this command do?
This command allows you to convert DataTable Row to DataTable


## When would I want to use this command?
Use this command when you want to convert DataTable Row to DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to fet rows from.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please enter the index of the Row (Default is Current Row)|Enter a valid DataRow index value|**0** or **1** or **-1** or **{vRowIndex}**|**-1** means index of the last row.|
|Please Specify the Variable Name To Assign The DataTable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ConvertDataTableRowToDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/11/22 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
