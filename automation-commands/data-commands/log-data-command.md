<!-- TITLE: Log Data Command -->
# Log Data Command
![Log Data](/uploads/automation-commands/log-data.png "Log Data")

## What does this command do?
This command allows you to write/append data to a log file

## When would I use this command?
Use this command when you want to write specific data to a file, such as logs for debugging.  You can choose between logging in the engine log file or your own custom file.

## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Select existing log file or enter a custom name	| Enter the required destination log file   	|  Choose **Engine Logs** or enter a custom value  	| Logs are generated in **taskt\Logs\{LogName}{Date}.txt**  	|
|Please enter the text/data to log  	|  Enter the text or variable values that should be written to the log 	| Enter variables encased in quotes [vText] or actual Text **Hello World!**  	|   	|


## Sample Task