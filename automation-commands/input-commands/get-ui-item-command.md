<!--TITLE: Get UI Item Command -->
<!-- SUBTITLE: a command in the Input Commands group -->
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
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 05:58 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
