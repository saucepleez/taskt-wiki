<!--TITLE: File Extraction Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# File Extraction Command


## What does this command do?



## When would I want to use this command?



## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select file type|Select source file type|Select **Type file**||
|Please indicate the file path or file URL to be extract|Enter or Select the path to the applicable file or enter file URL.|C:\temp\myfile.zip , [vFilePath] or https://temp.com/myfile.zip||
|Please select source file|Select source path|Select **File Path**, **File URL**||
|Please indicate the file path to be send after extract|Enter or Select the path to the applicable file or enter file URL.|C:\temp\ or [vFilePath]||
|Please select the variable to receive the list of extract files|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExtractFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
