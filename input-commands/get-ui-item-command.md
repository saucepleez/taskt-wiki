<!--TITLE: Get UI Item Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get UI Item Command


## What does this command do?
This command gets text from a Thick Application window


## When would I want to use this command?
Use this command when you want to get text from a specific handle in a window.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select the Window to Automate|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad**||
|Please select the Appropriate Item|Select one of the valid handles from the window|n/a|This list is populated after you select which window is required|
|Automation ID of the Item|n/a|n/a|This item is populated after you select which window handle name is required|
|Assign to Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ThickAppGetTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/06/21 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
