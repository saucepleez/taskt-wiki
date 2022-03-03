<!--TITLE: Resize Window Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Resize Window Command


## What does this command do?
This command resizes a window to a specified size.


## When would I want to use this command?
Use this command when you want to reize a window by name to a specific size on screen.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter or select the window that you want to resize.|Input or Type the name of the window that you want to resize.|**Untitled - Notepad** or **Current Window** or **{vWindow}**||
|Optional - Window title search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Please indicate the new required width (pixel) of the window.|Input the new width size of the window|**640** or **{vWidth}**|This number is limited by your resolution. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid width range could be 0-1920|
|Please indicate the new required height (pixel) of the window.|Input the new height size of the window|**480** or **{vHeight}**|This number is limited by your resolution. Maximum value should be the maximum value allowed by your resolution. For 1920x1080, the valid height range could be 0-1080|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ResizeWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/03/22 10:15 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
