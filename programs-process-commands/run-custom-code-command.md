<!--TITLE: Run Custom Code Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Run Custom Code Command


## What does this command do?
This command allows you to run C# code from the input


## When would I want to use this command?
Use this command when you want to run custom C# code commands.  The code in this command is compiled and run at runtime when this command is invoked.  This command only supports the standard framework classes.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Paste the C# code to execute|Enter the code to be executed or use the builder to create your custom C# code.  The builder contains a Hello World template that you can use to build from.|n/a||
|Optional - Supply Arguments|Enter arguments that the custom code will receive during execution|n/a||
|Optional - Select the variable to receive the output|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: RunCustomCodeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/22 11:50 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
