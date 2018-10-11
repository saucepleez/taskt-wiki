<!--TITLE: Run Query Command -->
<!-- SUBTITLE: a command in the Database Commands group -->
# Run Query Command


## What does this command do?
This command selects data from a database and applies it against a dataset


## When would I want to use this command?
Use this command to select data from a database.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please create a dataset variable name|Enter a custom name that references the dataset.|**MyData**||
|Please indicate the connection string|Enter a valid connection string to be used by the database.|Provider=Microsoft.ACE.OLEDB.12.0;Data Source=C:\myFolder\myAccessFile.accdb;Persist Security Info = False;||
|Please provide the query to run|Enter the query as text that should be executed.|**Select * From [table]**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: DatabaseRunQueryCommand
Parent Namespace: taskt.Core.AutomationCommands
This page was generated on 10/11/18 06:04 PM


## Help
[Report this document for inaccuracy](/#)
[Open/Report an issue on GitHub](/#)
[Ask a question on Gitter](/#)
