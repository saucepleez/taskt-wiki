<!--TITLE: Send Mouse Move Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Send Mouse Move Command


## What does this command do?
Simulates mouse movements


## When would I want to use this command?
Use this command to simulate the movement of the mouse, additionally, this command also allows you to perform a click after movement has completed.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the X position to move the mouse to|Input the new horizontal coordinate of the mouse, 0 starts at the left and goes to the right|**250** or **{vXPos}**|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1920|
|Please enter the Y position to move the mouse to|Input the new horizontal coordinate of the window, 0 starts at the left and goes down|**250** or **{vYPos}**|This number is the pixel location on screen. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid range could be 0-1080|
|Optional - Please indicate mouse click type if required (defualt is None)|Indicate the type of click required|Select from **Left Click**, **Middle Click**, **Right Click**, **Double Left Click**, **Left Down**, **Middle Down**, **Right Down**, **Left Up**, **Middle Up**, **Right Up** |You can simulate custom click by using multiple mouse click commands in succession, adding **Pause Command** in between where required.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: SendMouseMoveCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/27/22 11:01 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
