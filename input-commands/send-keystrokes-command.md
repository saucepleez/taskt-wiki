<!--TITLE: Send Keystrokes Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send Keystrokes Command


## What does this command do?
Sends keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send keystroke inputs to a window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Window name (ex. Untitled - Notepad, Current Window, {vWindowName})|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad** or **Current Window** or **{vWindowName}**||
|Please Enter text to send. (ex. Hello, ^s, {vText}, {WIN_KEY}, {WIN_KEY+R})|Enter the text that should be sent to the specified window.|**Hello, World!** or **{vEntryText}** or **{WIN_KEY}** or **{WIN_KEY+R}**|This command supports sending variables within brackets {vVariable}|
|Optional - Please Indicate if Text is Encrypted (default is Not Encrypted)|Indicate if the text in 'TextToSend' is Encrypted.|||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SendKeysCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/14/21 11:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
