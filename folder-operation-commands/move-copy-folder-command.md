<!--TITLE: Move/Copy Folder Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Move/Copy Folder Command


## What does this command do?
This command moves a folder to a specified destination


## When would I want to use this command?
Use this command to move a folder to a new destination.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Optional - Indicate whether to move or copy the folder (default is Move Folder)|Specify whether you intend to move the folder or copy the folder. Moving will remove the folder from the original path while Copying will not.|Select either **Move Folder** or **Copy Folder**||
|Please indicate the path to the source folder (ex. C:\temp\myfolder, {vFolderPath})|Enter or Select the path to the folder.|**C:\temp\myfolder** or **{vTextFolderPath}**||
|Please indicate the directory to move/copy to (ex. C:\temp\newfolder, {vFolderPath})|Enter or Select the new path to the file.|**C:\temp\newPath** or **{vTextFolderPath}**||
|Optional - Create folder if destination does not exist (default is No)|Specify whether the directory should be created if it does not already exist.|Select **Yes** or **No**||
|Optional - Delete folder if it already exists (defualt is No)|Specify whether the folder should be deleted first if it is already found to exist.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: MoveFolderCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/13/22 01:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
