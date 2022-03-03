<!--TITLE: Parse Dataset Row Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Parse Dataset Row Command


## What does this command do?
This command allows you to parse a dataset row column into a variable.


## When would I want to use this command?
Use this command when you want to extract data from a dataset variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the name of the variable containing the datasource|Select or provide a variable|**vSomeVariable**||
|Please Select Column Parse Type||||
|Specify Column Name or Index||||
|Please select the variable to receive the extracted column data|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Optional - Specify Alternate Row Number|If not executing within a loop, select the applicable index of the row required|**0** or **vRowNumber**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: ParseDatasetRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/03/22 10:15 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
