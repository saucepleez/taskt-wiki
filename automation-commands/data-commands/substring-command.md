<!--TITLE: Substring Command -->
<!-- SUBTITLE: a command in the Data Commands group -->
# Substring Command


## What does this command do?
This command allows you to trim a string


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please select a variable to modify|Select or provide a variable from the variable list|**vSomeVariable**||
|Start from Position|Indicate the starting position within the string|0 for beginning, 1 for first character, etc.||
|Optional - Length (-1 to keep remainder)|Indicate if only so many characters should be kept|-1 to keep remainder, 1 for 1 position after start index, etc.||
|Please select the variable to receive the changes|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: StringSubstringCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 05:58 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
