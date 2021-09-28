<!--TITLE: Loop Number Of Times Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Loop Number Of Times Command


## What does this command do?
This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to perform a series of commands a specified amount of times.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter how many times to perform the loop (ex. 5, {vNum})|Enter the amount of times you would like to perform the encased commands.|**5** or **10** or **{vNum}**||
|Optional - Define Start Index (Default: 0)|Enter the starting index of the loop.|**0** or **1** or **{vStartValue}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: BeginNumberOfTimesLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/21 11:00 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
