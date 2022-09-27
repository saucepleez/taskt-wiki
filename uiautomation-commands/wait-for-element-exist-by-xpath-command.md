<!--TITLE: Wait For Element Exist By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Wait For Element Exist By XPath Command


## What does this command do?
This command allows you to Wait until the AutomationElement exists using by XPath.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify AutomationElement Variable||**{vElement}**||
|Please specify search XPath||**//Button[@Name="OK"]** or **{vXPath}**|XPath does not support to use parent, following-sibling, and preceding-sibling for root element.|
|Please specify how many seconds to wait for the AutomationElement to exist||**10** or **{vWait}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: UIAutomationWaitForElementExistByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
