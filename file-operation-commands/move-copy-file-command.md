<!--TITLE: Move/Copy File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Move/Copy File Command


## What does this command do?
This command moves a file to a specified destination


## When would I want to use this command?
Use this command to move a file to a new destination.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Optional - Indicate whether to move or copy the file (default is Move File)|Specify whether you intend to move the file or copy the file.  Moving will remove the file from the original path while Copying will not.|Select either **Move File** or **Copy File**||
|Please indicate the path to the source file (ex. C:\temp\myfile.txt, {vFilePath})|Enter or Select the path to the file.|**C:\temp\myfile.txt** or **{vTextFilePath}**||
|Please indicate the directory to move/copy to (ex. C:\temp\new_folder, {vFolderPath})|Enter or Select the new path to the file.|**C:\temp\new path\** or **{vTextFolderPath}**||
|Optional - Create folder if destination does not exist (default is No)|Specify whether the directory should be created if it does not already exist.|Select **Yes** or **No**||
|Optional - Delete file if it already exists (default is No)|Specify whether the file should be deleted first if it is already found to exist.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: MoveFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/23/21 10:28 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
