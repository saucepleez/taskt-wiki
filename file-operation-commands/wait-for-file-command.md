<!--TITLE: Wait For File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Wait For File Command


## What does this command do?
This command waits for a file to exist at a specified destination


## When would I want to use this command?
Use this command to wait for a file to exist before proceeding.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the directory of the file (ex. C:\temp\myfile.txt, {vFilePath})|Enter or Select the path to the file.|**C:\temp\myfile.txt** or **{vTextFilePath}**||
|Indicate how many seconds to wait for the file to exist (ex. 10, {vWaitTime})|Specify how long to wait before an error will occur because the file is not found.|**10** or **20** or **{vWaitTime}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: WaitForFileToExistCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/26/21 05:14 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
