<!--TITLE: Wait For Folder To Exists Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Wait For Folder To Exists Command


## What does this command do?
This command waits for a folder to exist at a specified destination


## When would I want to use this command?
Use this command to wait for a folder to exist before proceeding.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path of the folder|Enter or Select the path to the folder.|**C:\temp\myfolder** or **{vFolderPath}**||
|Indicate how many seconds to wait for the file to exist|Specify how long to wait before an error will occur because the folder is not found.|**10** or **20** or **{vWaitTime}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: WaitForFolderToExistCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/18/22 11:33 午前


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
