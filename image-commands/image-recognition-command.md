<!--TITLE: Image Recognition Command -->
<!-- SUBTITLE: a command in the Image Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Image Recognition Command


## What does this command do?
This command attempts to find an existing image on screen.


## When would I want to use this command?
Use this command when you want to attempt to locate an image on screen.  You can subsequently take actions such as move the mouse to the location or perform a click.  This command generates a fingerprint from the comparison image and searches for it in on the desktop.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Capture the search image|Use the tool to capture an image||The image will be used as the image to be found on screen.|
|Optional - Offset X Coordinate (Default is 0)|Specify if an offset is required.|**0** or **100** or **{vXOffset}**|This will move the mouse X pixels to the right of the location of the image|
|Optional - Offset Y Coordinate (Default is 0)|Specify if an offset is required.|**0** or **100** or **{vYOffset}**|This will move the mouse X pixels down from the top of the location of the image|
|Optional - Please indicate mouse click type if required (Default is None)|Indicate the type of click required|Select from **Left Click**, **Middle Click**, **Right Click**, **Double Left Click**, **Left Down**, **Middle Down**, **Right Down**, **Left Up**, **Middle Up**, **Right Up** |You can simulate custom click by using multiple mouse click commands in succession, adding **Pause Command** in between where required.|
|Optional - Timeout (seconds, 0 for unlimited search time) (Default is 30)|Enter a timeout length if required.|**30** or **0** or **{vTimeout}**|Search times become excessive for colors such as white. For best results, capture a large color variance on screen, not just a white block.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: ImageRecognitionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/28/21 11:00 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
