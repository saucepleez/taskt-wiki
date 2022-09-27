<!--TITLE: Send Email Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send Email Command


## What does this command do?
This command allows you to send EMail using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an EMail and have access to SMTP server credentials to generate an EMail.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify SMTP Host Name|Define the host/service name that the script should use|**smtp.mymail.com** or **{vHost}**||
|Please specify SMTP Port|Define the port number that should be used when contacting the SMTP service|**25** or **587** or **{vPort}**||
|Optional - Please specify SMTP Username (Default is From Email)|Define the username to use when contacting the SMTP service|**username** or **{vUserName}**||
|Please specify SMTP Password|Define the password to use when contacting the SMTP service|**password** or **{vPassword}**||
|Please specify From Email Address|Specify how the 'From' field should appear.|**my-robot@company.com** or **{vFromMail}**||
|Please specify To Email Address|Specify the destination email that should be addressed.|**john@company.com** or **{vToMail}**||
|Optional - Please specify CC Email Address|Specify the destination email that should be addressed.|**tom@company.com** or **{vCCMail}**||
|Optional - Please specify BCC Email Address|Specify the destination email that should be addressed.|**bob@company.com** or **{vBCCMail}**||
|Optional - Please specify Email Subject|Define the text subject (or variable) that the email should have.|**Alert!** or **{vTitle}**||
|Optional - Please specify Email Message|Specify the message that should be sent.|**Everything ran ok at {DateTime.Now}**||
|Optional - Please specify Email Attachment File Path|Indicates the file path to attachment.|**c:\temp\file.txt** or **{vPath}**||
|Optional - Please specify Secure Option (Default is Auto)||||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|




























## Developer/Additional Reference
Automation Class Name: MailKitSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
