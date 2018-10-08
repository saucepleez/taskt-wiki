<!-- TITLE: Format Data Command -->
# Format Data Command
![Format Data](/uploads/automation-commands/format-data.png "Format Data")

## What does this command do?
This command allows you to modify a number or a date to a specified format and apply to a user-specified variable.  [Learn more about variables.](/concepts/variables)

## When would I use this command?
Use this command when you have a date or number (either free text or in a variable) that is required to be in a specific format.  For example, you may want a date without the time **8/6/17** instead of **8/6/17 12:34:52PM**.  You may also want to add decimal places to a number, convert a number into a percentage, or convert a number into currency.

## Command Parameters:

| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please supply the value or variable	| Select a variable (or enter text) which will contain the value of that is required to be formatted.   	|  **vSomeVariable** or text **12/31/2018 12:34:56PM**  	|  	|
|Please select the type of data  	|  Indicate whether the type of data is a number or date.  Please note, other types at this time are not supported.  	| Choose either **Number** or **Date**  	|  Selecting an invalid type will cause an error. 	|
|Specify required output format  	|  Enter the format specifier.  [You can find more about output formats here.](https://docs.microsoft.com/en-us/dotnet/standard/base-types/formatting-types)	| You could specify **MM/dd/yy** to trim off time from a date or **C2** to convert a number into currency.   	|   	|
|Please select the variable to receive output  	|  Select a variable which will contain the value of the formatted text.  	| vDestinationVariable  	| If you have 'Create Missing Variables During Execution' enabled, you can simply type the name of the variable and it will be created during the task execution.  	|

## Sample Task