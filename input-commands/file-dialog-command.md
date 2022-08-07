<!--TITLE: File Dialog Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# File Dialog Command


## What does this command do?
Show OpenFileDialog or SaveFileDialog


## When would I want to use this command?
Use this command when you want to select file to save or open.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Specify the type of dialog|OpenFileDialog or SaveFileDialog|**Open** or **Save**||
|Specify the value of the Filter property||**Text File (\*.txt)\|\*.txt** or **{vFilter}**||
|Optional - Specify the value of the FilterIndex property (Default is 1)||**1** or **2** or **{vIndex}**||
|Optional - Specify the value of the InitialDirectory property (Default is documents)||**C:\Users\myUser\Documents** or **{vFolderPath}**||
|Please select the variable to receive file name|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: FileDialogCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/07/22 12:05 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
