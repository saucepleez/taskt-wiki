<!--TITLE: Append Image Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Append Image Command


## What does this command do?
This command appends an image to a word document.


## When would I want to use this command?
Use this command when you want to append an image to a specific document.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Word** command|**myInstance** or **wordInstance**|Failure to enter the correct instance name or failure to first call **Create Word** command will cause an error|
|Please indicate the path to the image|Enter or Select the path to the image.|C:\temp\myimage.png or {vTextFilePath}||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: WordAppendImageCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
