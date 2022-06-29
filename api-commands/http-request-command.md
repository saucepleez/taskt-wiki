<!--TITLE: HTTP Request Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# HTTP Request Command


## What does this command do?
This command downloads the HTML source of a web page for parsing


## When would I want to use this command?
Use this command when you want to retrieve HTML of a web page without using browser automation.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the URL|Enter a valid URL that you want to collect data from.|http://mycompany.com/news or {vURL}||
|Execute Request as the currently logged on user?|Sets currently logged on user authentication information for the request.|Select 'Yes' or 'No'||
|Apply Result To Variable|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|










## Developer/Additional Reference
Automation Class Name: HTTPRequestCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/29/22 09:45 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
