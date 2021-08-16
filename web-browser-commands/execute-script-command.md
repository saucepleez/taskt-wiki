<!--TITLE: Execute Script Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Execute Script Command


## What does this command do?
This command allows you to execute a script in a Selenium web browser session.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name (ex. myInstance, {{vInstance})|Data not specified|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Please Enter the script code||||
|Optional - Please Enter the timeout in seconds (Default is 0)|If less than or equal to 0, wait for the script to finish.|**0** or **10** or **{vWaitTime}**|time >= 1 is async, time <= 0 is sync|
|Optional - Supply Argument|The value of the argument can be obtained with 'arguments[0]' in code.|||
|Optional - Please select the variable to receive the data|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: SeleniumBrowserExecuteScriptCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/16/21 01:36 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
