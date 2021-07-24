<!--TITLE: Remove DataRow Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Remove DataRow Command


## What does this command do?
This command allows you remove specified data rows.


## When would I want to use this command?
Use this command when you want to delete a specific row.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Name|Enter the name of your DataTable|**myData**||
|Please select overwrite option|Indicate whether this command should remove rows with all the constraints or remove them with 1 or more constraints|Select from **And** or **Or**||
|Please indicate tuples to delete column rows.|Enter a tuple containing the column name and item you would like to remove.|{ColumnName1,Item1},{ColumnName2,Item2}||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: RemoveDataRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/24/21 09:12 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
