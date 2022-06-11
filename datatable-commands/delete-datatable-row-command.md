<!--TITLE: Delete DataTable Row Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Delete DataTable Row Command


## What does this command do?
This command allows you to delete a DataTable Row


## When would I want to use this command?
Use this command when you want to delete a DataTable Row.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name to be delete a row|Enter a existing DataTable Variable Name|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify the Row Index to delete (Default is Current Row)||**0** or **1** or **-1** or **{vRow}**|**-1** means index of the last row.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: DeleteDataTableRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/11/22 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
