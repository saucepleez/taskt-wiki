<!--TITLE: Create Dataset Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Create Dataset Command


## What does this command do?
This command gets a range of cells and applies them against a dataset


## When would I want to use this command?
Use this command when you want to quickly iterate over Excel as a dataset.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please create a DataTable Variable Name|Indicate a unique reference name for later use|**vMyDataset** or **{vMyDataset}**||
|Please indicate the workbook file path|Enter or Select the path to the workbook file|**C:\temp\myfile.xlsx** or **{vFilePath}**|This command does not require Excel to be opened.  A snapshot will be taken of the workbook as it exists at the time this command runs.|
|Please indicate the sheet name|Indicate the specific sheet that should be retrieved.|**Sheet1** or **mySheet** or **{vSheet}**||
|Indicate if Header Row Exists|Select the necessary indicator|Select **Yes**, **No**.  Data will be loaded as column headers if **YES** is selected.||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: ExcelCreateDataSetCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/29/22 03:58 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
