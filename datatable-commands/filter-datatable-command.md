<!--TITLE: Filter DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Filter DataTable Command


## What does this command do?
This command allows you filter a DataTable into a new Datatable


## When would I want to use this command?
Use this command when you want to get specific rows of a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter the DataTable name you would like to filter through.|**myDataTable** or **{vMyDataTable}**||
|Please indicate the output DataTable Variable Name|Enter a unique DataTable name for future reference.|**newData** or **{vNewData}**||
|Please indicate tuples to filter by.|Enter a tuple containing the column name and item you would like to filter by.|{ColumnName1,Item1},{ColumnName2,Item2}||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: FilterDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/14/22 09:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
