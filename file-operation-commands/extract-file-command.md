<!--TITLE: Extract File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Extract File Command


## What does this command do?
This command extracts files from a compressed file


## When would I want to use this command?



## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the file path or location (ex. C:\myfile.zip, {vFilePath}, https://temp.com/myfile.zip)|Enter or Select the path to the applicable file or enter file URL.|**C:\temp\myfile.zip** , **{vFilePath}** or **https://temp.com/myfile.zip**||
|Please indicate the extraction folder (ex. C:\temp\myzip\, {vFolderPath})|Enter or Select the path to the applicable file or enter file URL.|**C:\temp\** or **{vFilePath}**||
|Optional - Create folder if destination does not exist (default is No)|Specify whether the directory should be created if it does not already exist.|Select **Yes** or **No**||
|Optional - Indicate the archive password (ex. mypass, {vPassword})|Enter archive files password.|**mypass** or {vPass}||
|Optional - Indicate the variable to receive a list of extracted file names|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: ExtractFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
