<!--TITLE: Create Browser Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Create Browser Command


## What does this command do?
This command allows you to create a new Selenium web browser session which enables automation for websites.


## When would I want to use this command?
Use this command when you want to create a browser that will eventually perform web automation such as checking an internal company intranet site to retrieve data


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|**myInstance** or **seleniumInstance**|**myInstance** or **seleniumInstance**|
|Instance Tracking (after task ends)|Specify if taskt should remember this instance name after the script has finished executing.|Select **Forget Instance** to forget the instance or **Keep Instance Alive** to allow subsequent tasks to call the instance by name.|Calling the **Close Browser** command or ending the browser session will end the instance.  This command only works during the lifetime of the application.  If the application is closed, the references will be forgetten automatically.|
|Please Select a Window State|Select the window state that the browser should start up with.|Select **Normal** to start the browser in normal mode or **Maximize** to start the browser in maximized mode.||
|Please specify Selenium command line options (optional)|Select optional options to be passed to the Selenium command.|user-data-dir=c:\users\public\SeleniumTasktProfile||
|Please Select a Browser Engine Type|Select the window state that the browser should start up with.|Select **Normal** to start the browser in normal mode or **Maximize** to start the browser in maximized mode.||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserCreateCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
