<!--TITLE: New Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# New Variable Command


## What does this command do?
This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please define the name of the new variable|Select or provide a variable from the variable list|**vSomeVariable**|If the variable exists, the value of the old variable will be replaced with the new one|
|Please define the input to be set to above variable (ex. Hello, {vNum})|Enter the input that the variable's value should be set to.|**Hello** or **{vNum}**|You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.|
|Optional - Define the action to take if the variable already exists (Default is Replace If Variable Exists)|Select the appropriate handler from the list|**Do Nothing If Variable Exists** or **Error If Variable Exists** or **Replace If Variable Exists**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: AddVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/06/21 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
