<!-- TITLE: Split Command -->
# Split Command
![Split](/uploads/automation-commands/split.png "Split")
## What does this command do?
This command allows you to split a string into multiple strings by specifying a delimiter.

## When would I use this command?
Use this command when you have a string such as **abc, def, ghi** and you want to split them into individual pieces **abc**, **def**, **ghi**

## Command Parameters:

| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please select a variable to split	| Select a variable (or enter text) which will contain the full string that needs to be split.   	|  **vSomeVariable** or text **123,456,789**  	|  	|
|Input Delimiter  	|  Indicate the delimiter by which to split the text  	| In this example use **,** (comma)	to split text by comma |  You can also specify **[crLF]** for splitting by new line or **[chars]** to split each character out	|
|Please select the list variable which will contain the results  	|  Enter a variable name such as **vList**| The variable will be automatically transformed to contain the List.  You can run a Loop List command and output the variable **[vList]** to get the data 	|   	|

## Sample Task