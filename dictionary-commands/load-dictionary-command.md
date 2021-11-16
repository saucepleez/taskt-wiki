<!--TITLE: Load Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Load Dictionary Command


## What does this command do?
This command Reads a Config file and stores it into a Dictionary.


## When would I want to use this command?
Use this command when you want to load a config file.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the Dictionary Variable Name|Enter a name for a Dictionary.|**myDictionary** or **{vDictionary}**||
|Please indicate the Workbook File Path|Enter or Select the path to the applicable file that should be loaded into the Dictionary.|**C:\temp\myfile.xlsx** or **{vFilePath}**|If file does not contain extension, supplement extensions supported by Excel.<br>If file does not contain folder path, file will be opened in the same folder as script file.|
|Please indicate the Sheet Name|Enter the sheet name of the workbook to be read.|**Sheet1** or **{vSheet}**|Sheet has one table|
|Please indicate the Key Column|Enter the key column name to create a Dictionary off of.|**Key** or **{vKeyColumn}**|This value is NOT Column Index Value like A, B. Please specify table column name.|
|Please indicate the Value Column|Enter a value column name to create a Dictionary off of.|**Value** or **{vValueColumn}**|This value is NOT Column Index Value like A, B. Please specify table column name.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: LoadDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/16/21 11:34 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
