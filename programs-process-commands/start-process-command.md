<!--TITLE: Start Process Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Start Process Command


## What does this command do?
This command allows you to start a program or a process.


## When would I want to use this command?
Use this command to start applications by entering their name such as 'chrome.exe' or a fully qualified path to a file 'c:/some.exe'


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the name or path to the program (ex. notepad, calc, C:\temp\myapp.exe, {vPath})|Provide a valid program name or enter a full path to the script/executable including the extension|**notepad** or **calc** or **c:\temp\myapp.exe** or **{vPath}**||
|Optional - Please enter any arguments (ex. -a, -version, {vArgs})|Enter any arguments or flags if applicable.|**-a** or **-version** or **{vArgs}**|You will need to consult documentation to determine if your executable supports arguments or flags on startup.|
|Optional - Wait for the process to complete? (Default is No)|Wait For Exit.|Select **Yes** or **No**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: StartProcessCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/14/21 11:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
