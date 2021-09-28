<!--TITLE: Parse JSON Item Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Parse JSON Item Command


## What does this command do?
This command allows you to parse a JSON object into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the JSON text or variable requiring extraction|Select or provide a variable or text value|**{"id":2}** or **{vSomeVariable}**||
|Specify a JSON extractor|Input a JSON token extractor|**$.id**||
|Please select the variable to receive the extracted JSON|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ParseJsonCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/21 11:00 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
