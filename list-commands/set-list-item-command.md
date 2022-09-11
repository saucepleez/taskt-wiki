<!--TITLE: Set List Item Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set List Item Command


## What does this command do?
This command allows you want to set an item in a List


## When would I want to use this command?
Use this command when you want to set an item in a List.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the List Variable Name.|Enter a existing List.|**myList** or **{myList}** or **[1,2,3]**||
|Optional - Please enter the index of the List item. (Default is Current Position)|Enter a valid List index value|**0** or **-1** or **{vIndex}**|**-1** means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.|
|Please Enter the Value of the Set||**1** or **{vValue}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: SetListItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/11/22 03:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
