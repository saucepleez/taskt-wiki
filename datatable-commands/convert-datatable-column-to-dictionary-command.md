<!--TITLE: Convert DataTable Column To Dictionary Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Convert DataTable Column To Dictionary Command


## What does this command do?
This command allows you to convert DataTable Column to Dictionary


## When would I want to use this command?
Use this command when you want to convert DataTable Column to Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name|Enter a existing DataTable to fet rows from.|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify Column type (Default is Column Name)||**Column Name** or **Index**||
|Please enter the Name or Index of the Column|Enter a valid Column index value|**id** or **0** or **{vColumn}** or **-1**|If **-1** is specified for Column Index, it means the last column.|
|Optional - Please enter the Dictionary Key prefix (Default is row)|Enter Dictionary Key Prefix|**row** or **{vPrefix}**|If enter **row**, Dictionary key is row0, row1, ...|
|Please Specify the Variable Name To Assign The Dictionary|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: ConvertDataTableColumnToDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
