<!--TITLE: Execute DLL Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Execute DLL Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the path to the DLL file|Enter or Select the path to the DLL File|C:\temp\myfile.dll or {vDLLFilePath}||
|Please select the name of the class that contains the method to be invoked|Provide the parent class name in the DLL.|Namespace should be included, myNamespace.myClass*||
|Please select the name of the method in the class to invoke|Provide the method name in the DLL to be invoked.|**GetSomething**||
|Please select the variable to receive the result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Please indicate the parameters (if required)|Select the 'Generate Parameters' button once you have indicated a file, class, and method.|||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: ExecuteDLLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/14/21 11:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
