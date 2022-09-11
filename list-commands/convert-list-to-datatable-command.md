<!--TITLE: Convert List To DataTable Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Convert List To DataTable Command


## What does this command do?
This command convert a List to a DataTable.


## When would I want to use this command?



## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the List to convert||**vList** or **{vList}**||
|Optional - Supply the DataTable Columns Name List||**vColumns** or **{vColumns}**|If Columns is empty, DataTable column is column0, column1, ...|
|Optional - When the number of items in the List is greater than the number of Columns (Default is Ignore)||||
|Optional - When the number of Columns is greater than the number of items in the List (Default is Ignore)||||
|Please select the variable to receive the DataTable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: ConvertListToDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/11/22 03:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
