<!--TITLE: Check Folder Exists Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Folder Exists Command


## What does this command do?
This command returns existance of folder paths from a specified location


## When would I want to use this command?
Use this command to return a existance of file paths from a specific location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Specify the path of the folder you want to check for existence (ex. C:\temp\myfolder, {vFolderPath})|Enter or Select the path to the file.|**C:\temp\myfolder** or **{vFolderPath}**||
|Specify the variable to assign the result||**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: CheckFolderExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/21/21 12:05 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
