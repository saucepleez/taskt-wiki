<!--TITLE: Math Calculation Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Math Calculation Command


## What does this command do?
This command allows you to perform a math calculation and apply it to a variable.


## When would I want to use this command?
Use this command when you want to perform a math calculation.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please supply the input to be computed|Specify either text or a variable that contains valid math.|**2+1** or **{vNum}+1**|You can use known numbers or variables.|
|Optional - Indicate Thousand Seperator|Enter the seperator used to identify decimal places||Typically a comma or a decimal point (period)|
|Optional - Indicate Decimal Seperator|Enter the seperator used to identify decimal places||Typically a comma or a decimal point (period)|
|Please select the variable to receive the math calculation|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: MathCalculationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/18/22 10:15 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
