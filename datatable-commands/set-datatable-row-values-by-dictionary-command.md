<!--TITLE: Set DataTable Row Values By Dictionary Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set DataTable Row Values By Dictionary Command


## What does this command do?
This command allows you to set a DataTable Row values to a DataTable by a Dictionary


## When would I want to use this command?
Use this command when you want to set a DataTable Row values to a DataTable by a Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataTable Variable Name to be setted a row|Enter a existing DataTable Variable Name|**myDataTable** or **{vMyDataTable}**||
|Optional - Please specify the Row index to set values (Default is Current Row)||**0** or **1** or **-1** or **{vIndex}**|**-1** means index of the last row.|
|Please specify the Dictionary Variable Name to set to the DataTable||||
|Optional - Please specify the if Dictionary key does not exists (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: SetDataTableRowValuesByDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/21/22 03:34 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
