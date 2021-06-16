<!--TITLE: Load Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands)


# Load Dictionary Command


## What does this command do?
This command Reads a Config file and stores it into a Dictionary.


## When would I want to use this command?
Use this command when you want to load a config file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Dictionary Name|Enter a name for a Dictionary.|**myDictionary**||
|Please indicate the workbook file path|Enter or Select the path to the applicable file that should be loaded into the Dictionary.|C:\temp\myfile.xlsx or [vFilePath]||
|Please indicate the Sheet Name|Enter the sheet name of the workbook to be read.|Sheet1||
|Please indicate the Key column|Enter the key column name to create a Dictionary off of.|keyColumn||
|Please indicate the Value Column|Enter a value column name to create a Dictionary off of.|valueColumn||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: LoadDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
