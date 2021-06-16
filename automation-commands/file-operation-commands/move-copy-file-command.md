<!--TITLE: Move/Copy File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Move/Copy File Command


## What does this command do?
This command moves a file to a specified destination


## When would I want to use this command?
Use this command to move a file to a new destination.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Indicate whether to move or copy the file|Specify whether you intend to move the file or copy the file.  Moving will remove the file from the original path while Copying will not.|Select either **Move File** or **Copy File**||
|Please indicate the path to the source file|Enter or Select the path to the file.|C:\temp\myfile.txt or [vTextFilePath]||
|Please indicate the directory to copy to|Enter or Select the new path to the file.|C:\temp\new path\ or [vTextFolderPath]||
|Create folder if destination does not exist|Specify whether the directory should be created if it does not already exist.|Select **Yes** or **No**||
|Delete file if it already exists|Specify whether the file should be deleted first if it is already found to exist.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: MoveFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
