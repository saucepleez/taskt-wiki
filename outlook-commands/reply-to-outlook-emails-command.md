<!--TITLE: Reply To Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Reply To Outlook Emails Command


## What does this command do?
This command allows you to reply to emails with outlook


## When would I want to use this command?
Use this command when you want to reply to emails with your currenty logged in outlook account


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Indicate whether to Reply or Reply All|Specify whether you intend to reply or reply all. Replying will reply to only the original sender. Reply all will reply to everyone.|Select either **Reply** or **Reply All**||
|Provide the source mail folder name|Enter the mail folder you want your emails to come from|**myData**||
|Provide a filter (Optional)|Enter an outlook filter string|[Subject] = 'Hello' and [SenderName] = 'Jane Doe'||
|Provide Email Body|Enter the body you want on your email to be sent.|**myData**||
|Select Email Body Type||Data not specified||
|Attachment File Path (Optional)|Enter the Filepath of the file you want attached.|c:sales reportsy06q4.xlsx||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: OutlookReplyToEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/21/21 12:05 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
