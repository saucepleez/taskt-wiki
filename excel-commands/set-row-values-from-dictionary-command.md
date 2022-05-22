<!--TITLE: Set Row Values From Dictionary Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Set Row Values From Dictionary Command


## What does this command do?
This command set Row values from Dictionary.


## When would I want to use this command?
Use this command when you want to set a Row values from Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the Row Index||**1** or **2** or **{vRow}**||
|Optional - Please Specify Column Type (Default is Range)||**Range** or **RC**||
|Please Enter the Start Column Location||**A** or **1** or **{vColumn}**||
|Please Enter the End Column Location||**A** or **1** or **{vColumn}**||
|Please specify the Dictionary Variable Name to set|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Optional - Please specify the Value type to set (Default is Cell)||**Cell** or **Formula** or **Format** or **Color** or **Comment**||
|Optional - Please specify If Dictionary Items not enough (Default is Ignore)||**Ignore** or **Error**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|




















## Developer/Additional Reference
Automation Class Name: ExcelSetRowValuesFromDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/22/22 08:44 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
