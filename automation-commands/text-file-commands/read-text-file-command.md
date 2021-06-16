<!--TITLE: Read Text File Command -->
<!-- SUBTITLE: a command in the Text File Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Read Text File Command


## What does this command do?
This command reads text data into a variable


## When would I want to use this command?
Use this command when you want to read data from text files.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the file|Enter or Select the path to the text file.|C:\temp\myfile.txt or [vTextFilePath]||
|Please define where the text should be stored|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ReadTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
