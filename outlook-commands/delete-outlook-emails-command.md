<!--TITLE: Delete Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Delete Outlook Emails Command


## What does this command do?
This command allows you to delete emails with outlook


## When would I want to use this command?
Use this command when you want to delete emails with your currenty logged in outlook account


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Provide the source mail folder name|Enter the mail folder you want your emails to come from|**myData**||
|Provide a filter (Required)|Enter an outlook filter string|[Subject] = 'Hello' and [SenderName] = 'Jane Doe'||
|Delete read emails only|Specify whether to delete read email messages only|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: OutlookDeleteEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/24/21 09:12 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
