<!--TITLE: Delete DataTable Column Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Delete DataTable Column Command


## What does this command do?
This command allows you to delete a column to a DataTable


## When would I want to use this command?
Use this command when you want to delete a column to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to add rows to.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify the Column type (Default is Column Name)||**Column Name** or **Index**||
|Please specify the Column Name to delete||**0** or **newColumn** or **{vColumn}** or **-1**|If **-1** is specified for Column Index, it means the last column.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: DeleteDataTableColumnCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
