<!--TITLE: Forward Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Forward Outlook Emails Command


## What does this command do?
This command allows you to forward emails with outlook


## When would I want to use this command?
Use this command when you want to forward emails with your currenty logged in outlook account


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Provide the source mail folder name|Enter the mail folder you want your emails to come from|**myData**||
|Provide a filter (Optional)|Enter an outlook filter string|[Subject] = 'Hello' and [SenderName] = 'Jane Doe'||
|Indicate Recipients (; delimited)|Enter the Email Addresses of the recipients in semicolon seperated values|test@test.com;test2@test.com||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: OutlookForwardEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/29/22 09:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
