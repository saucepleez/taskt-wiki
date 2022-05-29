<!--TITLE: Get DataRow Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get DataRow Command


## What does this command do?
This command allows you to get a DataRow from a DataTable


## When would I want to use this command?
Use this command when you want to add a datarow to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to fet rows from.|**myDataTable** or **{vMyDataTable}**||
|Please enter the index of the DataRow|Enter a valid DataRow index value|**0** or **{vRowIndex}**||
|Please Specify the Variable Name To Assign The DataRow|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: GetDataRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/29/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
