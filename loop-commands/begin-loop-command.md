<!--TITLE: Begin Loop Command -->
<!-- SUBTITLE: a command in the Loop Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Begin Loop Command


## What does this command do?
This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false


## When would I want to use this command?
Use this command when you want to check if a statement is 'true' or 'false' and subsequently loop actions based on either condition. Any 'BeginLoop' command must have a following 'EndLoop' command.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select type of Loop Command|Select the necessary comparison type.|Select **Value**, **Window Name Exists**, **Active Window Name Is**, **File Exists**, **Folder Exists**, **Web Element Exists**, **Error Occured**||
|Additional Parameters|Select the required comparison parameters.|n/a||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: BeginLoopCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/20/22 08:40 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
