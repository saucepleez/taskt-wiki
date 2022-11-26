<!--TITLE: Take Screenshot Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Take Screenshot Command


## What does this command do?
This command takes a screenshot and saves it to a location


## When would I want to use this command?
Use this command when you want to take and save a screenshot.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Window name|Input or Type the name of the window that you want to take a screenshot of.|**Untitled - Notepad** or **Current Window** or **Desktop** or **{vWindow}**||
|Please indicate the path to save the image|Data not specified|**c:\Temp\image.png** or **{vPath}**|If file does not contain extensin, suppliment png extension.<br>If file does not contain folder path, file will be saved in the same folder as script file.<br>If file path contains FileCounter variable, it will be replaced by a number that will become the name of a non-existent file.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: ScreenshotCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
