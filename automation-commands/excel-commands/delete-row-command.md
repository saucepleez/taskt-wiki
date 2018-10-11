<!--TITLE: Delete Row Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Delete Row Command


## What does this command do?
This command allows you to delete a specified row in Excel


## When would I want to use this command?
Use this command when you want to delete an entire row from the current sheet.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **seleniumInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Indicate the row number to delete|Enter the number of the row that should be deleted.|1, 5, [vNumber]||
|Data not specified|Indicate whether the row below will be shifted up to replace the old row.|Select 'Yes' or 'No'||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExcelDeleteRowCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:14 PM


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
