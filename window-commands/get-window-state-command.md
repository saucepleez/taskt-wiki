<!--TITLE: Get Window State Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Window State Command


## What does this command do?
This command returns a state of window name.


## When would I want to use this command?
Use this command when you want to get a window state.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter or select the window that you want to check existence.|Input or Type the name of the window that you want to check existence.|**Untitled - Notepad** or **Current Window** or **{vWindow}**||
|Optional - Window title search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Specify the variable to assign the result||**vSomeVariable**|Restore is **1**, Minimize is **2**, Maximize is **3**|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: GetWindowStateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/13/21 09:43 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
