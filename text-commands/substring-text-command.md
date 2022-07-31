<!--TITLE: Substring Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Substring Text Command


## What does this command do?
This command allows you to trim a Text


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a variable or text|Select or provide a variable or text value|**Hello** or **{vText}**||
|Please specify Start from Position|Indicate the starting position within the string|**1** or **{vPosition}**|0 for beginning, 1 for first character, etc.|
|Optional - Please specify Extract Length (-1 to keep remainder) (Default is -1)|Indicate if only so many characters should be kept|**1** or **-1** or **{vLength}**|-1 to keep remainder, 1 for 1 position after start index.|
|Please select the variable to receive the Result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: SubstringTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
