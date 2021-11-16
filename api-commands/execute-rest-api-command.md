<!--TITLE: Execute REST API Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Execute REST API Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the Base URL (ex. http://mysite.com)|Define any API endpoint which contains the full URL.|**https://example.com** or **{vMyUrl}**||
|Please enter the endpoint (Ex. /v2/endpoint)|Define any API endpoint which contains the full URL.|**/v2/getUser/1** or **{vMyUrl}**||
|Please select method type|Select the necessary method type.|Data not specified||
|Advanced REST Parameters|Specify a list of advanced parameters.|n/a||
|Basic REST Parameters|Specify default search parameters|n/a|Once you have clicked on a valid window the search parameters will be populated.  Enable only the ones required to be a match at runtime.|
|Apply Result To Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Please select method type|Select the necessary method type.|Data not specified||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


















## Developer/Additional Reference
Automation Class Name: RESTCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/16/21 11:34 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
