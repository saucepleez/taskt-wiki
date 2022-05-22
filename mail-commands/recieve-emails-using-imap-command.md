<!--TITLE: Recieve Emails Using IMAP Command -->
<!-- SUBTITLE: a command in the Mail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Recieve Emails Using IMAP Command


## What does this command do?
This command allows you to get emails using IMAP protocol.


## When would I want to use this command?
Use this command when you want to get emails using IMAP protocol.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify IMAP Host Name|Define the host/service name that the script should use|**imap.mymail.com** or **{vHost}**||
|Please specify IMAP Port|Define the port number that should be used when contacting the IMAP service|**143** or **993** or **{vPort}**||
|Please specify IMAP Username|Define the username to use when contacting the IMAP service|**username** or **{vUserName}**||
|Please specify IMAP Password|Define the password to use when contacting the IMAP service|**password** or **{vPassword}**||
|Optional - Please specify Secure Option (Default is Auto)||||
|Please specify Variable Name to Store Mail List||**vMailList** or **{vMailList}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: MailKitRecieveEmailsUsingIMAPCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/22/22 08:44 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
