<!--TITLE: Wait For Window To Exist Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Wait For Window To Exist Command


## What does this command do?
This command waits for a window to exist.


## When would I want to use this command?
Use this command when you want to explicitly wait for a window to exist before continuing script execution.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter or select the window name that you are waiting for to exist.|Input or Type the name of the window that you want to wait to exist.|**Untitled - Notepad** or **Current Window** or **{vWindow}**||
|Optional - Window title search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Indicate how many seconds to wait before an error should be raised.|Specify how many seconds to wait before an error should be invoked|**5** or **{vWaitTime}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: WaitForWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/23/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
