<!--TITLE: Switch Browser Window Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Switch Browser Window Command


## What does this command do?
This command allows you to create a new Selenium web browser session which enables automation for websites.


## When would I want to use this command?
Use this command when you want to create a browser that will eventually perform web automation such as checking an internal company intranet site to retrieve data


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.|**myInstance** or **seleniumInstance**|**myInstance** or **seleniumInstance**|
|Please Select type of match to make|Select an option which best fits to the search type you would like to make.|Select one of the provided options.||
|Please define a match specification|Select an option which best fits to the specification you would like to make.|Select one of the provided options.||
|Indicate if search is case-sensitive|Select an option which best fits to the specification you would like to make.|Select one of the provided options.||
|Please provide the parameter to match (ex. Window URL, Window Title, Handle ID)|Data not specified|Enter in 'http://www.url.com' or 'Welcome to Homepage'||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserSwitchWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
