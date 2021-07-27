<!--TITLE: Remote Task Command -->
<!-- SUBTITLE: a command in the Remote Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Remote Task Command


## What does this command do?
This command allows you to execute a task remotely on another taskt instance


## When would I want to use this command?
Use this command when you want to execute a command on another client that has local listener enabled


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please enter the IP:Port (ex. 192.168.2.200:19312)|Define any IP endpoint which is enabled for local listening.|**https://example.com** or **{vMyUrl}**||
|Select Parameter Type|Select the necessary parameter.|Data not specified||
|Execution Preference|Select the necessary execution preference.|Data not specified||
|Script Parameter Data|Specify the data, typically either raw data, local file, or remote file|n/a||
|Request Timeout (ms)|Enter the length of time to wait before the request times out |Data not specified||
|Please select the variable to receive the response|Select or provide a variable from the variable list|**vSomeVariable**|If you have enabled the setting **Create Missing Variables at Runtime** then you are not required to pre-define your variables, however, it is highly recommended.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|


## Developer/Additional Reference
Automation Class Name: RemoteTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/27/21 10:46 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
