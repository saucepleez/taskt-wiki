<!--TITLE: Unload Task Command -->
<!-- SUBTITLE: a command in the Task Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Unload Task Command


## What does this command do?
This command runs tasks.


## When would I want to use this command?
Use this command when you want to run another task.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Select a Task to Pre-Load.  Use Run Task with the same path to execute.|Enter or Select the valid path to the file.|**c:\temp\mytask.xml** or **{vScriptPath}**||
|Unload Error Preference|Select the appropriate corresponding action to take once the element has been located|Select from **Invoke Click**, **Left Click**, **Right Click**, **Middle Click**, **Double Left Click**, **Clear Element**, **Set Text**, **Get Text**, **Get Attribute**, **Wait For Element To Exist**, **Get Count**|Selecting this field changes the parameters that will be required in the next step|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|








## Developer/Additional Reference
Automation Class Name: UnloadTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/01/22 11:50 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
