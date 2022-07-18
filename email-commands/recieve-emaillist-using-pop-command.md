<!--TITLE: Recieve EMailList Using POP Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Recieve EMailList Using POP Command


## What does this command do?
This command allows you to get EMailList(EMails) using POP protocol.


## When would I want to use this command?
Use this command when you want to get MailList(EMails) using POP protocol. Result Variable Type is EMailList.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please specify POP Host Name|Define the host/service name that the script should use|**pop.mymail.com** or **{vHost}**||
|Please specify POP Port|Define the port number that should be used when contacting the POP service|**110** or **995** or **{vPort}**||
|Please specify POP Username|Define the username to use when contacting the POP service|**username** or **{vUserName}**||
|Please specify POP Password|Define the password to use when contacting the POP service|**password** or **{vPassword}**||
|Optional - Please specify Secure Option (Default is Auto)||||
|Please specify Variable Name to Store EMailList||**vMailList** or **{vMailList}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: MailKitRecieveEmailListUsingPOPCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/18/22 11:33 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
