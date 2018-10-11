<!--TITLE: Split Command -->
<!-- SUBTITLE: a command in the Data Commands group -->
# Split Command


## What does this command do?
This command allows you to split a string


## When would I want to use this command?
Use this command when you want to split a single text or variable into multiple items


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a variable to split|Select or provide a variable from the variable list|**vSomeVariable**||
|Input Delimiter|Declare the character that will be used to seperate. [crLF] can be used for line breaks and [chars] can be used to split each digit/letter|[crLF], [chars], ',' (comma - with no single quote wrapper)||
|Please select the list variable which will contain the results|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: StringSplitCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 05:58 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
