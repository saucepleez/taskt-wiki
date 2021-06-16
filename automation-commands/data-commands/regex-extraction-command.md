<!--TITLE: RegEx Extraction Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# RegEx Extraction Command


## What does this command do?
This command allows you to perform advanced string formatting using RegEx.


## When would I want to use this command?
Use this command when you want to perform an advanced RegEx extraction from a text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please supply the value or variable (ex. [vSomeVariable])|Select or provide a variable or text value|**Hello** or **vSomeVariable**||
|Input the RegEx Extractor Pattern|Enter the RegEx extractor pattern that should be used to extract the text|^([\w\-]+)|If an extractor splits each word in a sentence, for example, you will need to specify the associated index of the word that is required.|
|Select Matching Group Index|Define the index of the result|1|The extractor will split multiple patterns found into multiple indexes.  Test which index is required to retrieve the value or create a better/more define extractor.|
|Please select the variable to receive the RegEx result|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: RegExExtractorCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
