<!--TITLE: Format Data Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Format Data Command


## What does this command do?
This command allows you to apply formatting to a string


## When would I want to use this command?
Use this command when you want to apply specific formatting to text or a variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please supply the value or variable (ex. {DateTime.Now}, 2500, {vNum})|Specify either text or a variable that contains a date or number requiring formatting|{DateTime.Now}, 1/1/2000, 2500|You can use known text or variables.|
|Please select the type of data|Indicate the source type|Choose **Date** or **Number** or **Path**||
|Specify required output format (ex. yy/MM/dd, hh:mm, #.0, file)|Specify if a specific string format is required.|**MM/dd/yy**, **hh:mm**, **C2**, **D2**, **file** etc.|Path supports **file**, **folder**, **filewithoutextension**, **extension**, **drive**|
|Please select the variable to receive output|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: FormatDataCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/24/21 09:12 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
