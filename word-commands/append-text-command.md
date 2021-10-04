<!--TITLE: Append Text Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Append Text Command


## What does this command do?
This command appends text to a word document.


## When would I want to use this command?
Use this command when you want to append text to a specific document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please Enter the Text Variable Name to Set|Enter the text value that will be set.|Hello World or {vText}||
|Select or Enter the text font name|Specify the font name.|Select **Arial**||
|Select or Enter the text font size|Specify the font name.|Select **14**||
|Select Bold|Specify whether the text font should be bold.|Select **Yes** or **No**||
|Select Italic|Specify whether the text font should be italic.|Select **Yes** or **No**||
|Select Underline|Specify whether the text font should be underlined.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


















## Developer/Additional Reference
Automation Class Name: WordAppendTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/04/21 10:21 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
