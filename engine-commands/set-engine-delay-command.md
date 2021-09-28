<!--TITLE: Set Engine Delay Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Engine Delay Command


## What does this command do?
This command allows you to set delays between execution of commands in a running instance.


## When would I want to use this command?
Use this command when you want to change the execution speed between commands.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Set Delay between commands (in milliseconds). (ex. 2500, {vWait})|Enter a specific amount of time in milliseconds (ex. to specify 8 seconds, one would enter 8000) or specify a variable containing a value.|**250** or **{vVariableSpeed}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






## Developer/Additional Reference
Automation Class Name: SetEngineDelayCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/21 11:00 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
