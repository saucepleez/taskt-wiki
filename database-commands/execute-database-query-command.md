<!--TITLE: Execute Database Query Command -->
<!-- SUBTITLE: a command in the Database Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Execute Database Query Command


## What does this command do?
This command allows you to perform a database query and apply the result to a dataset


## When would I want to use this command?
Use this command to select data from a database.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **seleniumInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Define Query Execution Type||||
|Define Query to Execute||||
|Define Query Parameters||||
|Apply Result To Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: DatabaseExecuteQueryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/27/22 11:01 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
