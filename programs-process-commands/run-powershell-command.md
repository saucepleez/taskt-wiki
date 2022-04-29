<!--TITLE: Run Powershell Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Run Powershell Command


## What does this command do?
This command allows you to run a powershell script and wait for it to exit before proceeding.


## When would I want to use this command?
Use this command when you want to run a powershell script and wait for it to close before taskt continues executing.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Enter the path to the powershell script (ex. C:\temp\myscript.ps, {vScriptPath})|Enter a fully qualified path to the script, including the script extension.|**C:\temp\myscript.ps1** or **{vScriptPath}**|This command differs from **Start Process** because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using **Start Process** instead.<br>If file does not contain extensin, supplement ps1 or bat extension.<br>If file does not contain folder path, file will be opened in the same folder as script file.|
|Enter Powershell Command Arguments|Enter any necessary arguments|||
|Convert variables before execution|Select the necessary option.|Data not specified||
|Optional - Select the variable to receive the output|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: RunPowershellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/29/22 03:58 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
