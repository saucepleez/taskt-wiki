<!--TITLE: Write Text File Command -->
<!-- SUBTITLE: a command in the Text File Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Write Text File Command


## What does this command do?
This command writes specified data to a text file


## When would I want to use this command?
Use this command when you want to write data to text files.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the file (ex. C:\temp\myfile.txt, {vFilePath}|Enter or Select the path to the text file.|**C:\temp\myfile.txt** or **{vTextFilePath}**|If file does not contain extensin, supplement txt automatically.<br>If file does not contain folder path, file will be saved in the same folder as script file.<br>If file path contains FileCounter variable, it will be replaced by a number that will become the name of a non-existent file.|
|Please indicate the text to be written. [crLF] inserts a newline.|Indicate the text should be written to files.|**{vText}** or **Hello World!**||
|Optional - Please select overwrite option (Default is Overwrite)|Indicate whether this command should append the text to or overwrite all existing text in the file|Select from **Append** or **Overwrite**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: WriteTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/26/21 05:14 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
