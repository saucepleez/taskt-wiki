<!--TITLE: Split Range By Column Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Split Range By Column Command


## What does this command do?
This command gets text from a specified Excel Range and splits it into separate ranges by column.


## When would I want to use this command?
Use this command when you want to split a range into separate ranges.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Excel** command|**myInstance** or **excelInstance**|Failure to enter the correct instance name or failure to first call **Create Excel** command will cause an error|
|Please Enter the First Cell Location (ex. A1 or B2)|Enter the actual location of the cell.|A1, B10, {vAddress}||
|Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)|Enter the actual location of the cell.|A1, B10, {vAddress}||
|Please Enter the Column Name|Enter the name of the column you wish to split by.|ColA, {vColumn}||
|Please indicate the output directory|Enter or Select the new directory for the split Excel Files.|C:\temp\new path\ or {vTextFolderPath}||
|Indicate the File Type to save as|Specify the file format type for the split ranges|Select either **xlsx* or **csv**||
|Assign DataTable List to Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


















## Developer/Additional Reference
Automation Class Name: ExcelSplitRangeByColumnCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/22 10:14 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
