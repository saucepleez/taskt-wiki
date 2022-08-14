<!--TITLE: Get Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Outlook Emails Command


## What does this command do?
This command allows you to get emails and attachments with outlook


## When would I want to use this command?
Use this command when you want to get emails and attachments with your currenty logged in outlook account


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Provide the source mail folder name|Enter the mail folder you want your emails to come from|**myData**||
|Provide a filter (Optional)|Enter an outlook filter string|[Subject] = 'Hello' and [SenderName] = 'Jane Doe'||
|Get unread emails only|Specify whether to retrieve unread email messages only|Select **Yes** or **No**||
|Mark emails as read|Specify whether to retrieve unread email messages only|Select **Yes** or **No**||
|Please indicate the output directory for the messages|Enter or Select the path to the directory.|C:\temp\myfolder or {vTextFolderPath}||
|Assign MailItem List to variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Save messages and attachments|Specify whether to save the email attachments to a local directory|Select **Yes** or **No**||
|Please indicate the output directory for the attachments|Enter or Select the path to the directory.|C:\temp\myfolder or {vTextFolderPath}||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|




















## Developer/Additional Reference
Automation Class Name: OutlookGetEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/14/22 09:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
