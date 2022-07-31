<!--TITLE: Add List Item Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Add List Item Command


## What does this command do?
This command allows you to add list item.


## When would I want to use this command?
Use this command when you want to add list item.  You can even use variables to modify other variables.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a List Variable Name to modify|Select or provide a variable from the variable list|**vList** or **{vList}**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Please define the input to be added to the variable|Enter the input that the variable's value should be set to.|**Hello** or **{vValue}**|You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: AddListItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
