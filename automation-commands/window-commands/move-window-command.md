<!--TITLE: Move Window Command -->
<!-- SUBTITLE: a command in the Window Commands group -->
# Move Window Command


## What does this command do?
This command moves a window to a specified location on screen.


## When would I want to use this command?
Use this command when you want to move an existing window by name to a certain point on the screen.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Select or Type a window Name|Input or Type the name of the window that you want to move.|**Untitled - Notepad**||
|Please select the X position to move the window to.|Input the new horizontal coordinate of the window, 0 starts at the left and goes to the right|0|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920|
|Please select the Y position to move the window to.|Input the new vertical coordinate of the window, 0 starts at the top and goes downwards|0|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: MoveWindowCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:04 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
