<!--TITLE: Rename File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Rename File Command


## What does this command do?
This command renames a file at a specified destination


## When would I want to use this command?
Use this command to rename an existing file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the source file (ex. C:\temp\myfile.txt, {vFilePath})|Enter or Select the path to the file.|**C:\temp\myfile.txt** or **{vTextFilePath}**||
|Please indicate the new file name (with extension) (ex. newfilename.txt, {vFileName})|Specify the new file name including the extension.|**newfile.txt** or **{vNewFileName}**|Changing the file extension will not automatically convert files.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: RenameFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/03/22 01:55 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
