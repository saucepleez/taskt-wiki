<!--TITLE: Get Dictionary Item Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get Dictionary Item Command


## What does this command do?
This command allows you to get value in Dictionary


## When would I want to use this command?
Use this command when you want to get value in Dictionary.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please input The Dictionary Variable||**myDictionary** or **{vMyDic}**||
|Optional - Please indicate the key for the Dictionary (Default is Current Position)||**key1** or **{vKeyName}**|If it is empty, it will be the value of Current Position, which can be used for Loop List command.|
|Please indicate the variable to apply result|Enter a unique dataset name that will be used later to traverse over the data|**vMyData** or **{myData}**||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: GetDictionaryValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/31/22 04:25 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
