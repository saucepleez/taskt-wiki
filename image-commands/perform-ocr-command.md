<!--TITLE: Perform OCR Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Perform OCR Command


## What does this command do?
This command allows you to covert an image file into text for parsing.


## When would I want to use this command?
Use this command when you want to convert an image into text.  You can then use additional commands to parse the data.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select Image to OCR|Enter or Select the path to the image file.|**c:\temp\myimages.png** or **{vFileName}**||
|Apply OCR Result To Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: OCRCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/29/22 03:58 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
