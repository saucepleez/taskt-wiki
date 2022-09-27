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
|Please Enter the Window name|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad** or **Current Window** or **{vWindowName}**||
|Optional - Window name search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Please Enter text to send.|Enter the text that should be sent to the specified window.|**Hello, World!** or **^s** or **{vEntryText}** or **{WIN_KEY}** or **{WIN_KEY+R}**|This command supports sending variables within brackets {vVariable}|
|Optional - Please Indicate if Text is Encrypted (Default is Not Encrypted)|Indicate if the text in 'TextToSend' is Encrypted.|||
|Optional - Please specify waiting time after keystrokes (ms) (Default is 500)||**500** or **{vWaitTime}|If less than 100 is specified, it will be 100|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: SendKeysCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
