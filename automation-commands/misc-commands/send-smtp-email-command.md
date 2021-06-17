<!--TITLE: Send SMTP Email Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send SMTP Email Command


## What does this command do?
This command allows you to send email using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an email and have access to SMTP server credentials to generate an email.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Host Name|Define the host/service name that the script should use|**smtp.gmail.com**||
|Port|Define the port number that should be used when contacting the SMTP service|**587**||
|Username|Define the username to use when contacting the SMTP service|**username**||
|Password|Define the password to use when contacting the SMTP service|**password**||
|From Email|Specify how the 'From' field should appear.|myRobot@company.com||
|To Email|Specify the destination email that should be addressed.|jason@company.com||
|Subject|Define the text subject (or variable) that the email should have.|**Alert!** or **{vStatus}**||
|Body|Specify the message that should be sent.|**Everything ran ok at {DateTime.Now}**||
|Attachment Path (Optional)|Indicates the file path to attachment.|**c:\temp\file.txt**||
|SSL Validation|Select the appropriate option|Select from **Validate SSL**, **Bypass SSL Validation**|This field manages whether taskt will attempt to validate the SSL connection|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: SMTPSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/17/21 09:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
