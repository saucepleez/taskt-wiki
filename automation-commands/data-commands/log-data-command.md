<!--TITLE: Log Data Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Log Data Command


## What does this command do?
This command logs data to files.


## When would I want to use this command?
Use this command when you want to log custom data to a file for debugging or analytical purposes.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select existing log file or enter a custom name.|Indicate the file name where logs should be appended to|Select 'Engine Logs' or specify your own file|Date and Time will be automatically appended to the file name.  Logs are all saved in taskt Root\Logs folder|
|Please enter the text to log.|Indicate the value of the text to be saved.|Third Step Complete, [vVariable], etc.||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: LogDataCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:14 PM


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
