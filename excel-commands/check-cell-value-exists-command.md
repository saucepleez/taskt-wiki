<!--TITLE: Check Cell Value Exists Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Cell Value Exists Command


## What does this command do?
This command checks existance value from a specified Excel Cell.


## When would I want to use this command?
Use this command when you want to get a value from a specific cell.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the Cell Location|Enter the actual location of the cell.|**A1** or **B10** or **{vAddress}**||
|Please select the variable to receive the result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Optional - Value type (Default is Cell)||**Cell** or **Formula** or **Format** or **Color** or **Comment**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








### Addtional Info about &quot;Value type (Default is Cell)&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Cell|Check cell has value or not|||
|Formula|Check cell has formula or not|||
|Back Color|Check back color is not white|||




## Developer/Additional Reference
Automation Class Name: ExcelCheckCellValueExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/21/22 03:34 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
