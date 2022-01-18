<!--TITLE: Open Document Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Open Document Command


## What does this command do?
This command opens an Word Document.


## When would I want to use this command?
Use this command when you want to open an existing Word Document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error.|
|Please indicate the workbook file path|Enter or Select the path to the applicable file that should be opened by Excel.|C:\temp\myfile.docx or {vFilePath}|If file does not contain extensin, supplement extentions supported by Word.<br>If file does not contain folder path, file will be opened in the same folder as script file.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: WordOpenDocumentCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/18/22 10:15 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
