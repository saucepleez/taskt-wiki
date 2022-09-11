<!--TITLE: Set Column Values From DataTable Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Column Values From DataTable Command


## What does this command do?
This command set Column values from DataTable.


## When would I want to use this command?
Use this command when you want to set Column values from DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Optional - Please Specify Excel Column Type (Default is Range)||**Range** or **RC**||
|Please Enter the Excel Column Location or Index||**A** or **1** or **{vColumn}**||
|Optional - Please Enter the Start Row Index (Default is 1)||**1** or **2** or **{vRow}**||
|Optional - Please Enter the End Row Index (Default is End of DataTable Row)||**1** or **2** or **{vRow}**||
|Please specify the DataTable Variable Name to set|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Please Enter the DataTable Column Index||**0** or **1** or **{vColumn}**||
|Optional - Please specify the Value type to get (Default is Cell)||**Cell** or **Formula** or **Format** or **Color** or **Comment**||
|Optional - Please specify If DataTable Items not enough (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






















## Developer/Additional Reference
Automation Class Name: ExcelSetColumnValuesFromDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/11/22 03:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
