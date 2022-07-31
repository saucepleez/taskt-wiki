<!--TITLE: Set DataTable Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set DataTable Value Command


## What does this command do?
This command allows you to set the DataTable value


## When would I want to use this command?
Use this command when you want to set the DataTable value.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify the Column value type (Default is Column Name)||**Index** or **Column Name**||
|Please specify the Column Name or Index||**0** or **id** or **{vColumn}** or **-1**|If **-1** is specified for Column Index, it means the last column.|
|Optional - Please specify the Row Index (Default is Current Row)||**0** or **1** or **-1** or **{vIndex}**|**-1** means index of the last row.|
|Please Specify the Value to set DataTable|Select or provide a variable from the variable list|**value** or **123** or **{vValue}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: SetDataTableValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
