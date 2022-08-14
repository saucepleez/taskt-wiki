<!--TITLE: Run Script Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Run Script Command


## What does this command do?
This command allows you to run a script or program and wait for it to exit before proceeding.


## When would I want to use this command?
Use this command when you want to run a script (such as vbScript, javascript, or executable) but wait for it to close before taskt continues executing.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter the path to the script (ex. C:\temp\myscript.vbs, {vScriptPath})|Enter a fully qualified path to the script, including the script extension.|**C:\temp\myscript.vbs** or **{vScriptPath}**|This command differs from **Start Process** because this command blocks execution until the script has completed.  If you do not want to stop while the script executes, consider using **Start Process** instead.If file does not contain extensin, supplement extensions supported by cmd.<br>If file does not contain folder path, file will be opened in the same folder as script file.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






## Developer/Additional Reference
Automation Class Name: RunScriptCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/14/22 09:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
