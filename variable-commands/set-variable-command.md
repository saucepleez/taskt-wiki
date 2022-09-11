<!--TITLE: Set Variable Command -->
<!-- SUBTITLE: a command in the Variable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Variable Command


## What does this command do?
This command allows you to modify variables.


## When would I want to use this command?
Use this command when you want to modify the value of variables.  You can even use variables to modify other variables.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a variable to modify|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Please define the input to be set to above variable (ex. Hello, 1, {vNum})|Enter the input that the variable's value should be set to.|**1** or **Hello** or {vNum}|You can use variables in input if you encase them within brackets {vName}.  You can also perform basic math operations.|
|Optional - Convert Variables in Input Text Above (Default is Yes)|Select the necessary option.|Data not specified|If {vNum} has '1' and you select 'Yes', variable will be assigned '1'. If you select 'No', variable will be assigned '{vNum}'.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: VariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/11/22 03:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
