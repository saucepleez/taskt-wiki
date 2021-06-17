<!--TITLE: Create Browser Command -->
<!-- SUBTITLE: a command in the IE Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Create Browser Command


## What does this command do?
This command allows you to create a new IE web browser session.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Data not specified|Data not specified|Data not specified|
|Instance Tracking (after task ends)|Specify if taskt should remember this instance name after the script has finished executing.|Select **Forget Instance** to forget the instance or **Keep Instance Alive** to allow subsequent tasks to call the instance by name.|Calling the **Close Browser** command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.|
|Please Enter the URL to navigate to|Data not specified|Data not specified|Data not specified|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: IEBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/17/21 09:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
