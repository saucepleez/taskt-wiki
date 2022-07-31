<!--TITLE: Switch Browser Frame Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Switch Browser Frame Command


## What does this command do?
This command allows you to create a new Selenium web browser session which enables automation for websites.


## When would I want to use this command?
Use this command when you want to create a browser that will eventually perform web automation such as checking an internal company intranet site to retrieve data


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name (ex. myInstance , {vInstance})|Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Indicate Frame Selection Type|Select an option which best fits to the specification you would like to make.|Select one of the provided options.||
|Optional - Frame Search Parameter (If Selection Type is 'Index' or 'Name of ID', please enter)|Data not specified|Index: **0** or **{vIndex}**, Name/ID: **top** or **{vName}**|If selection type is 'Index', default index is 0.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: SeleniumBrowserSwitchFrameCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
