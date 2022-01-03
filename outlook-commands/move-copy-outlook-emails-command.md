<!--TITLE: Move/Copy Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Move/Copy Outlook Emails Command


## What does this command do?
This command allows you to move/copy emails with outlook


## When would I want to use this command?
Use this command when you want to move/copy emails with your currenty logged in outlook account


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Indicate whether to Move or Copy the emails|Specify whether you intend to move or copy the Emails. Moving will remove the emails from the original folder while Copying will not.|Select either **Move Emails** or **Copy Emails**||
|Provide the source mail folder name|Enter the mail folder you want your emails to come from|**myData**||
|Provide a filter (Optional)|[Subject] = 'Hello' and [SenderName] = 'Jane Doe'|[Subject] = 'Hello'||
|Move/Copy unread emails only|Specify whether to move/copy unread email messages only|Select **Yes** or **No**||
|Provide the destination folder name|Enter or Select the path to the directory.|**myData**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: OutlookMoveEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/03/22 01:55 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
