<!--TITLE: Send Hotkey Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send Hotkey Command


## What does this command do?
Sends keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send keystroke inputs to a window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Window name|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad** or **Current Window** or **{vWindowName}**||
|Optional - Window name search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Please select Hotkey to Send.|Enter the text that should be sent to the specified window.|||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






### Addtional Info about &quot;Please select Hotkey to Send.&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|New|Send Ctrl + N|||
|New Window|Send Ctrl + Shift + N|||
|Open|Send Ctrl + O|||
|Print|Send Ctrl + P|||
|Save|Send Ctrl + S|||
|Save As|Send Ctrl + Shift + S|||
|Undo|Send Ctrl + Z|||
|Cut|Send Ctrl + X|||
|Copy|Send Ctrl + C|||
|Paste|Send Ctrl + V|||
|Delete|Send Delete|||
|Search|Send Ctrl + E|||
|Find|Send Ctrl + F|||
|Find Next|Send F3|||
|Find Previous|Send Shift + F3|||
|Replace|Send Ctrl + H|||
|Go To|Send Ctrl + G|||
|Select All|Send Ctrl + A|||




## Developer/Additional Reference
Automation Class Name: SendHotkeyCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/03/22 10:15 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
