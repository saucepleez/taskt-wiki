<!-- TITLE: RegEx Extraction Command -->
# Regex Extraction Command
![Regex Extraction](/uploads/automation-commands/regex-extraction.png "Regex Extraction")

## What does this command do?
This is an advanced command which allows you to parse text from a larger piece of text based on a text specifier.

## When would I use this command?
Use this command when you want to parse a value out of text or a variable.  

## Command Parameters:

| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please supply the value or variable	| Select a variable (or enter text) which will contain the value of that is required to be formatted   	|  **vSomeVariable** or text **Hello World!**  	|  	|
|Input the RegEx extractor pattern  	|  Input the required extraction pattern  	| Input an extractor pattern such as **^([\w\-]+)** 	|  You can find help online to build the required extractor patterns. 	|
|Select matching group index  	| If the pattern returns 1 or more items, specify which index will contain the text you want	| You could specify any number such as **0, 1, 2, etc.**   	|   	|
|Please select the variable to receive the RegEx result  	|  Select a variable which will contain the parsed text.  	| vDestinationVariable  	| If you have 'Create Missing Variables During Execution' enabled, you can simply type the name of the variable and it will be created during the task execution.  	|

## Sample Task