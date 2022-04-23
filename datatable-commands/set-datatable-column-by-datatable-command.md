<!--TITLE: Set DataTable Column By DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set DataTable Column By DataTable Command


## What does this command do?
This command allows you to set a column to a DataTable by a DataTable


## When would I want to use this command?
Use this command when you want to set a column to a DataTable by a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to add rows to.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify Column type (Default is Column Name)||**Column Name** or **Index**||
|Please specify the Column Name to set||**0** or **newColumn** or **{vNewColumn}** or **-1**|If **-1** is specified for Column Index, it means the last column.|
|Please specify the DataTable to set new Column values||**vDataTable** or **{vDataTable}**||
|Optional - If the number of rows is less than the DataTable to set (Default is Ignore)||**Ignore** or **Add Rows** or **Error**||
|Optional - If the number of DataTable items is less than the rows to setted DataTable (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: SetDataTableColumnValuesByDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/23/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
