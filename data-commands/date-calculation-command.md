<!--TITLE: Date Calculation Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Date Calculation Command


## What does this command do?
This command allows you to build a date and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a date calculation.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please supply the date value or variable|Specify either text or a variable that contains the start date.|**{DateTime.Now}** or **1/1/2000**|You can use known text or variables.|
|Please Select a Calculation Method|Select the necessary operation|Select From Add Seconds, Add Minutes, Add Hours, Add Days, Add Years, Subtract Seconds, Subtract Minutes, Subtract Hours, Subtract Days, Subtract Years |Data not specified|
|Please supply the increment value|Enter how many units to increment by|15, {vIncrement}|You can use negative numbers which will do the opposite, ex. Subtract Days and an increment of -5 will Add Days.|
|Optional - Specify String Format|Specify if a specific string format is required.|**MM/dd/yy** or **hh:mm** or etc.||
|Please select the variable to receive the date calculation|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: DateCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/27/22 11:01 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
