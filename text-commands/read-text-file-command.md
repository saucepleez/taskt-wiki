<!--TITLE: Read Text File Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Read Text File Command


## What does this command do?
This command allows you to read text file into a variable


## When would I want to use this command?
Use this command when you want to read data from text files.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the file|Enter or Select the path to the text file.|**C:\temp\myfile.txt** or **{vTextFilePath}** or **http://example.com/mytext.txt** or **{vURL}**|If file does not contain extensin, supplement txt automatically.<br>If file does not contain folder path, file will be opened in the same folder as script file.|
|Optional - Please select the read type (Default is Content)|Select the appropriate window state required|**Content** or **Line Count**||
|Please Specify Variable the text should be stored|Select or provide a variable from the variable list|**vTextFile** or **{vTextFile}**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: ReadTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/14/22 09:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
