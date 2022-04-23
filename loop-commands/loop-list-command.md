<!--TITLE: Loop List Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Loop List Command


## What does this command do?
This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to iterate over each item in a list, or a series of items.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please input the list variable to be looped (ex. {vList}, [1,2,3])|Enter a variable which contains a list of items|**{vMyList}** or **[1,2,3]**|Use this command to iterate over the results of the Split command.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






## Developer/Additional Reference
Automation Class Name: BeginListLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/23/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
