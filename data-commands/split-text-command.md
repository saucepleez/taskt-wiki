<!--TITLE: Split Text Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Split Text Command


## What does this command do?
This command allows you to split a string


## When would I want to use this command?
Use this command when you want to split a single text or variable into multiple items


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select variable or text to split|Select or provide a variable or text value|**Hello** or **{vText}**||
|Input Delimiter (ex. [crLF] for new line, [chars] for each char, ',' , {vChar})|Declare the character that will be used to seperate. [crLF] can be used for line breaks and [chars] can be used to split each digit/letter|[crLF], [chars], ',' (comma - with no single quote wrapper)||
|Please select the list variable which will contain the results|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: StringSplitCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 10/24/21 02:26 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
