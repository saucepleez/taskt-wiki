<!--TITLE: Set Column Values From List Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Column Values From List Command


## What does this command do?
This command set Column values from List.


## When would I want to use this command?
Use this command when you want to set Column values from List.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Optional - Please Specify Column Type (Default is Range)||**Range** or **RC**||
|Please Enter the Column Location or Index||**A** or **1** or **{vColumn}**||
|Please Enter the Start Row Index||**1** or **2** or **{vRow}**||
|Please Enter the End Row Index||**1** or **2** or **{vRow}**||
|Please specify the List Variable Name to set|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Optional - Please specify the Value type to get (Default is Cell)||**Cell** or **Formula** or **Format** or **Color** or **Comment**||
|Optional - Please specify If List Items not enough (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|




















## Developer/Additional Reference
Automation Class Name: ExcelSetColumnValuesFromListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/27/22 11:01 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)