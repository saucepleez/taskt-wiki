<!--TITLE: Get An Element Values As DataTable Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Get An Element Values As DataTable Command


## What does this command do?
This command allows you to get Attributes value for an Element As DataTable.


## When would I want to use this command?
Use this command when you want to get Attributes value for an Element As DataTable.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Browser** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Please Specify Element Search Method|Select the specific search type that you want to use to isolate the element in the web page.|Select **Find Element By XPath**, **Find Element By ID**, **Find Element By Name**, **Find Element By Tag Name**, **Find Element By Class Name**, **Find Element By CSS Selector**, **Find Element By Link Text**||
|Please Specify Element Search Parameter|Specifies the parameter text that matches to the element based on the previously selected search type.|If search type **Find Element By ID** was specified, for example, given <div id='name'></div>, the value of this field would be **name**||
|Please Specify Element Index||**0** or **1** or **{vIndex}**||
|Please specify Attributes Name to Get||**id** or **Text** or **textContent** or **{vAttribute}**||
|Please Specify DataTable Variable Name to store result||||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: SeleniumBrowserGetAnElementValuesAsDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 05/16/22 09:36 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
