<!--TITLE: Get DataRow Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get DataRow Value Command


## What does this command do?
This command allows you to get a DataRow Value from a DataTable


## When would I want to use this command?
Use this command when you want to add a datarow to a DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the DataRow Variable Name|Enter a existing DataRow to get Values from.|**myDataRow** or **{vMyDataRow}**||
|Optional - Select value by Index or Column Name (Default is Index)|Select whether the DataRow value should be found by index or column name|Select from **Index** or **Column Name**||
|Please enter the index of the DataRow Value|Enter a valid DataRow index value|**0** or **ColName** or **{vIndex}**||
|Please Specify the Variable to Assign the Value|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|












## Developer/Additional Reference
Automation Class Name: GetDataRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/06/21 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
