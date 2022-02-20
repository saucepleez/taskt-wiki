<!--TITLE: Add DataTable Column And Fill Values By List Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Add DataTable Column And Fill Values By List Command


## What does this command do?
This command allows you to add a column to a DataTable by a List


## When would I want to use this command?
Use this command when you want to add a column to a DataTable by a List.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to add rows to.|**myDataTable** or **{vMyDataTable}**||
|Please specify the Column Name to add||**newColumn** or **{vNewColumn}**||
|Please specify the List to set new Column values||**vList** or **{vList}**||
|Optional - If Colmun Name is already exists (Default is Ignore)||**Ignore** or **Overwrite** or **Error**||
|Optional - If the number of rows is less than the List (Default is Ignore)||**Ignore** or **Add Rows** or **Error**||
|Optional - If the number of List items is less than the rows (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: AddDataTableColumnAndFillValuesByListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/20/22 08:40 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
