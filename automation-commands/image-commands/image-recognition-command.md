<!--TITLE: Image Recognition Command -->
<!-- SUBTITLE: a command in the Image Commands group -->
# Image Recognition Command


## What does this command do?
This command attempts to find an existing image on screen.


## When would I want to use this command?
Use this command when you want to attempt to locate an image on screen.  You can subsequently take actions such as move the mouse to the location or perform a click.  This command generates a fingerprint from the comparison image and searches for it in on the desktop.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Capture the search image|Use the tool to capture an image||The image will be used as the image to be found on screen.|
|Offset X Coordinate - Optional|Specify if an offset is required.|0 or 100|This will move the mouse X pixels to the right of the location of the image|
|Offset Y Coordinate - Optional|Specify if an offset is required.|0 or 100|This will move the mouse X pixels down from the top of the location of the image|
|Please indicate mouse click type if required|Indicate the type of click required|Select from **Left Click**, **Middle Click**, **Right Click**, **Double Left Click**, **Left Down**, **Middle Down**, **Right Down**, **Left Up**, **Middle Up**, **Right Up** |You can simulate custom click by using multiple mouse click commands in succession, adding **Pause Command** in between where required.|
|Timeout (seconds, 0 for unlimited search time)|Enter a timeout length if required.||Search times become excessive for colors such as white. For best results, capture a large color variance on screen, not just a white block.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ImageRecognitionCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:04 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
