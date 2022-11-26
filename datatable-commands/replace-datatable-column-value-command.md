<!--TITLE: Replace DataTable Column Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Replace DataTable Column Value Command


## What does this command do?
This command allows you to Replace Column values.


## When would I want to use this command?
Use this command when you want to Replace Column values.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a DataTable Variable Name to Replace||**vTable** or **{vTable}**||
|Optional - Please specify Column type (Default is Column Name)||**Column Name** or **Index**||
|Please enter the Name or Index of the Column|Enter a valid Column index value|**id** or **0** or **{vColumn}** or **-1**|If **-1** is specified for Column Index, it means the last column.|
|Please select replace target value type||**Text** or **Number**||
|Please select replace action||||
|Additional Parameters||||
|Please specify replace value||**newValue** or **{vNewValue}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


















## Developer/Additional Reference
Automation Class Name: ReplaceDataTableColumnValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
