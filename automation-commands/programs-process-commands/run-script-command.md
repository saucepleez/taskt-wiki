<!--TITLE: Run Script Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group -->
# Run Script Command


## What does this command do?
This command allows you to run a script or program and wait for it to exit before proceeding.


## When would I want to use this command?
Use this command when you want to run a script (such as vbScript, javascript, or executable) but wait for it to close before taskt continues executing.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter the path to the script|Enter a fully qualified path to the script, including the script extension.|**C:\temp\myscript.vbs**|This command differs from **Start Process** because this command blocks execution until the script has completed.  If you do not want to stop while the script executes, consider using **Start Process** instead.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: RunScriptCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:04 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
