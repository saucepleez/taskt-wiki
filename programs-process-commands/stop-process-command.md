<!--TITLE: Stop Process Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Stop Process Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter the process name to be stopped (ex. calc, notepad, {vPath})|Provide the program process name as it appears as a process in Windows Task Manager|**notepad** or **calc** or **{vPath}**|The program name may vary from the actual process name.  You can use Thick App commands instead to close an application window.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






## Developer/Additional Reference
Automation Class Name: StopProcessCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/16/22 09:36 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
