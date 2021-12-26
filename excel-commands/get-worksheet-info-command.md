<!--TITLE: Get Worksheet Info Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Worksheet Info Command


## What does this command do?
This command allows you to get a sheet info.


## When would I want to use this command?
Use this command when you want to launch a new instance of Excel.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|**myInstance** or **{vInstance}**||
|Please select the sheet name||**mySheet** or **Current Sheet** or **{vSheet}**||
|Please select the information type||**Name** or **Visible** or **Is first sheet** or **Is last sheet** or **Next sheet** or **Previous sheet** or **Sheet index**||
|Please select the variable to receive a sheet info|Select or provide a variable from the variable list|**vSomeVariable**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ExcelGetWorksheetInfoCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/26/21 05:14 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
