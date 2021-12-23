<!--TITLE: Get Folders Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Folders Command


## What does this command do?
This command returns a list of folder directories from a specified location


## When would I want to use this command?
Use this command to return a list of folder directories from a specific location.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the source folder (ex. C:\temp\myfolder, {vFolderPath})|Enter or Select the path to the folder.|**C:\temp\myfolder** or **{vTextFolderPath}**||
|Optional - Please indicate the folder name filter (Default is empty and searched all folders) (ex. hello, {vFolderName})|Enter or Select the folder name filter.|**hello** or **{vFolderName}**||
|Optional - Please indicate the file name search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Specify the variable to assign the folder path list|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: GetFoldersCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/23/21 10:28 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
