<!--TITLE: Filter DataTable Column By Row Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Filter DataTable Column By Row Value Command


## What does this command do?
This command allows you to Filter Columns by reference to Row values.


## When would I want to use this command?
Use this command when you want to Filter Columns by reference to Row values.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a DataTable Variable Name to Filter||**vTable** or **{vTable}**||
|Please enter the Index of the Row|Enter a valid Column index value|**id** or **0** or **{vRow}** or **-1**|If **-1** is specified for Row Index, it means the last row.|
|Please select filter target value type||**Text** or **Number**||
|Please select filter action||||
|Additional Parameters||||
|Please select a DataTable Variable Name of the Filtered DataTable||**vNewTable** or **{vNewTable}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: FilterDataTableColumnByRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
