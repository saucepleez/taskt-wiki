<!--TITLE: Extraction Text Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Extraction Text Command


## What does this command do?
This command allows you to perform advanced string extraction.


## When would I want to use this command?
Use this command when you want to extract a piece of text from a larger text or variable


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Supply the value or variable requiring extraction|Select or provide a variable or text value|**Hello** or **{vText}**||
|Please select text extraction type|Select the type of extraction that is required.|Select from Before Text, After Text, Between Text||
|Extraction Parameters|Define the required extraction parameters, which is dependent on the type of extraction.|n/a||
|Please select the variable to receive the extracted text|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|






### Addtional Info about &quot;Extraction Parameters&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Extract All After Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All After Text &amp; Skip Past Occurences||||
|Extract All Before Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Before Text &amp; Skip Past Occurences||||
|Extract All Between Text &amp; Leading Text|The beginning of the text to be extracted|**Hello** or **{vStart}**||
|Extract All Between Text &amp; Trailing Text|The end of text to be extracted|**Hello** or **{vEnd}**||
|Extract All Between Text &amp; Skip Past Occurences||||






## Developer/Additional Reference
Automation Class Name: ExtractionTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/13/22 01:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
