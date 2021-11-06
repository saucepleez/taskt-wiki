<!--TITLE: Move Window Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Move Window Command


## What does this command do?
This command moves a window to a specified location on screen.


## When would I want to use this command?
Use this command when you want to move an existing window by name to a certain point on the screen.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter or select the window that you want to move.|Input or Type the name of the window that you want to move.|**Untitled - Notepad** or **Current Window** or **{vWindow}**||
|Optional - Window title search method (Default is Contains)||**Contains** or **Start with** or **End with** or **Exact match**||
|Please indicate the new X horizontal coordinate (pixel) for the window's location.  0 starts at the left of the screen.|Input the new horizontal coordinate of the window, 0 starts at the left and goes to the right|**0** or **{vXPos}** or **Current Position**|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920|
|Please indicate the new Y vertical coordinate (pixel) for the window's location.  0 starts at the top of the screen.|Input the new vertical coordinate of the window, 0 starts at the top and goes downwards|**0** or **{vYPos}** or **Current Position**|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: MoveWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/06/21 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
