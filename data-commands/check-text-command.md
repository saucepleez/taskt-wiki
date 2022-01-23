<!--TITLE: Check Text Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Check Text Command


## What does this command do?
This command allows you to check a string


## When would I want to use this command?
Use this command when you want to select a subset of text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the value or variable to check|Select or provide a variable or text value|**Hello** or **{vText}**||
|Select the check method||**Contains** or **Starts with** or **Ends with** or **Index of** or **Last Index of**||
|Select the check method||**Ha** or **{vSearchedText}**||
|Optional - Case sensitive (Default is Yes)|Indicate if only so many characters should be kept|**Yes** or **No**||
|Please select the variable to receive the result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










### Addtional Info about &quot;Please select the variable to receive the result&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Contains|Result is TRUE or FALSE|||
|Start with|Result is TRUE or FALSE|||
|End with|Result is TRUE or FALSE|||
|Index of|Result is a found position. If not found, the result is -1.|||
|Last Index of|Result is the last position found. If not found, the result is -1.|||




## Developer/Additional Reference
Automation Class Name: CheckTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/23/22 09:09 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
