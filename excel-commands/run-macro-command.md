<!--TITLE: Run Macro Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Run Macro Command


## What does this command do?
This command runs a macro.


## When would I want to use this command?
Use this command when you want to get a run a specific macro in the Excel workbook.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the macro name|Enter the name of the macro as it exists in the spreadsheet|**Macro1** or **Module1.Macro1** or **{vMacro}**||
|Optional - Please Enter the macro argument1|Enter the value of the macro argument|**1** or **Hello** or **{vArgument}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ExcelRunMacroCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/23/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
