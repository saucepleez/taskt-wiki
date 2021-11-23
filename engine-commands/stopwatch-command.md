<!--TITLE: Stopwatch Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Stopwatch Command


## What does this command do?
This command allows you to stop a program or a process.


## When would I want to use this command?
Use this command to close an application by its name such as 'chrome'. Alternatively, you may use the Close Window or Thick App Command instead.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter the instance name of the Stopwatch|Provide a unique instance or way to refer to the stopwatch|**myStopwatch**, **{vStopWatch}**||
|Enter the Stopwatch Action|Provide a unique instance or way to refer to the stopwatch|||
|Apply Result To Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Optional - Specify String Format (ex. hh:mm)|Specify if a specific string format is required.|MM/dd/yy, hh:mm, etc.||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: StopwatchCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/23/21 07:05 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
