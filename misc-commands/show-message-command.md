<!--TITLE: Show Message Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Show Message Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the message to be displayed.|Specify any text that should be displayed on screen.  You may also include variables for display purposes.|**Hello World** or **{vMyText}**||
|Optional - Close After X (Seconds) - 0 to bypass (Default is 0)|Specify how many seconds to display on screen. After the amount of seconds passes, the message box will be automatically closed and script will resume execution.|**0** or **{vTime}**|**0** to remain open indefinitely or **5** to stay open for 5 seconds.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: MessageBoxCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/27/22 11:01 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
