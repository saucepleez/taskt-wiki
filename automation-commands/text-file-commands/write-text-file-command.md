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
|Please indicate the path to the file|Enter or Select the path to the text file.|C:\temp\myfile.txt or [vTextFilePath]||
|Please indicate the text to be written. [crLF] inserts a newline.|Indicate the text should be written to files.|**[vText]** or **Hello World!**||
|Please select overwrite option|Indicate whether this command should append the text to or overwrite all existing text in the file|Select from **Append** or **Overwrite**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: WriteTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
