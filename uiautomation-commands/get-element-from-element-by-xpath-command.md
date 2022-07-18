<!--TITLE: Get Element From Element By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Element From Element By XPath Command


## What does this command do?
This command allows you to get AutomationElement from AutomationElement using by XPath.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify AutomationElement Variable||**{vElement}**||
|Please specify search XPath||**//Button[@Name="OK"]** or **{vXPath}**|XPath does not support to use parent, following-sibling, and preceding-sibling for root element.|
|Please specify a Variable to store Result AutomationElement||**vElement** or **{vElement}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: UIAutomationGetElementFromElementByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/18/22 11:33 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
