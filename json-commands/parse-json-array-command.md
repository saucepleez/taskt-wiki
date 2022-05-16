<!--TITLE: Parse JSON Array Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Parse JSON Array Command


## What does this command do?
This command allows you to parse a JSON Array into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the JSON Array or Variable|Select or provide a variable or json array value|**[1,2,3]** or **[{obj1},{obj2}]** or **{vArrayVariable}**||
|Please select the variable to receive the list|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: ParseJSONArrayCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/16/22 09:36 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
