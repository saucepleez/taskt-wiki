<!--TITLE: Pause Script Command -->
<!-- SUBTITLE: a command in the Misc Commands group. [Go To Automation Commands Overview](/automation-commands) -->
# Pause Script Command


## What does this command do?
This command pauses the script for a set amount of time specified in milliseconds.


## When would I want to use this command?
Use this command when you want to pause your script for a specific amount of time.  After the specified time is finished, the script will resume execution.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Amount of time to pause for (in milliseconds).|Enter a specific amount of time in milliseconds (ex. to specify 8 seconds, one would enter 8000) or specify a variable containing a value.|**8000** or **[vVariableWaitTime]**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: PauseCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:09 PM


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
