<!--TITLE: Get Element From Window By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Element From Window By XPath Command


## What does this command do?
This command allows you to get AutomationElement from Window Name using by XPath.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify Window Name||**{vElement}**||
|Optional - Please select Window name search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Please specify search XPath||**//Button[@Name="OK"]** or **{vXPath}**|XPath does not support to use parent, following-sibling, and preceding-sibling for root element.|
|Please specify a Variable to store Result AutomationElement||**vElement** or **{vElement}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: UIAutomationGetElementFromWindowByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
