<!--TITLE: Add DataTable Columns And Fill Values By DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Add DataTable Columns And Fill Values By DataTable Command


## What does this command do?
This command allows you to add a columns to a DataTable by a DataTable


## When would I want to use this command?
Use this command when you want to add a columns to a DataTable by a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to add rows to.|**myDataTable** or **{vMyDataTable}**||
|Please specify the DataTable to set new Column values||**vDataTable** or **{vDataTable}**||
|Optional - If Colmun Name is already exists (Default is Ignore)||**Ignore** or **Overwrite** or **Error**||
|Optional - If the number of rows is less than the DataTable to set new Column (Default is Ignore)||**Ignore** or **Add Rows** or **Error**||
|Optional - If the number of DataTable to set new Column is less than the rows (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: AddDataTableColumnsAndFillValuesByDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/23/22 09:09 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
