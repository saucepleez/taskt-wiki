<!--TITLE: Text Extraction Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Text Extraction Command


## What does this command do?
This command allows you to perform advanced string extraction.


## When would I want to use this command?
Use this command when you want to extract a piece of text from a larger text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the value or variable requiring extraction (ex. Hello, {vText})|Select or provide a variable or text value|**Hello** or **{vSomeVariable}**||
|Please select text extraction type|Select the type of extraction that is required.|Select from Before Text, After Text, Between Text||
|Extraction Parameters|Define the required extraction parameters, which is dependent on the type of extraction.|n/a||
|Please select the variable to receive the extracted text|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: TextExtractorCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/17/21 09:39 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
