<!--TITLE: Take Screenshot Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Take Screenshot Command


## What does this command do?
This command allows you to take a screenshot in Selenium web browser session.


## When would I want to use this command?
Use this command when you want to take a screenshot from the current displayed webpage within the web browser.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name (ex. myInstance, {vInstance})|Enter the unique instance name that was specified in the **Create Browser** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Please define folder where the screenshot should be stored (ex. C:\screenshots, {vPath})|Enter folder path or select folder from the list to define where the screenshot should be stored|**C:\screenshots\** or **{vPath}**||
|Please define the screenshot file name (no extension needed) (ex. screenshot_001, {vName})|Enter file name for the screenshot|**screenshot_001** or **{vName}**|png image|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: SeleniumBrowserTakeScreenshotCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/24/21 02:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
