<!--TITLE: Insert JSON Array Item Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Insert JSON Array Item Command


## What does this command do?
This command allows you to insert item to JSON Array.


## When would I want to use this command?



## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Specify the JSON Variable Name||**{vSomeVariable}**||
|Please Specify a JSON extractor (JSONPath)|Input a JSON token extractor|**$.id**||
|Optional - Please Specify Insert Index (Default is Last Item)||**0** or **1** or **{vIndex}**||
|Please Specify Value to Insert||**Hello** or **{vValue}**||
|Optional - Please Specify Value Type to Insert (Default is Auto)||**Text** or **Number** or **bool** or **Object** or **Array**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: InsertJSONArrayItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/26/22 09:32 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
