<!--TITLE: Get DataTable Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get DataTable Value Command


## What does this command do?
This command allows you to get the DataTable value


## When would I want to use this command?
Use this command when you want to get the DataTable value.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify the Column value type (Default is Column Name)||**Index** or **Column Name**||
|Please specify the Column Name or Index||**0** or **id** or **{vIndex}** or **{vColumn}**||
|Please specify the Row Index||**0** or **{vIndex}**||
|Please Specify the Variable Name To Assign the Value|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: GetDataTableValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/23/21 10:28 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)