<!-- TITLE: Substring Command -->
# Substring Command
![Substring](/uploads/automation-commands/substring.png "Substring")
## What does this command do?
This command allows you to select a piece of text based on character occurence.

## When would I use this command?
Use this command when you want only a piece of text and you know the position where the text occurs. For example, if you had text with a leading plus sign such as **+18005501394** you could use this command to take everything after the plus sign and assign it to a variable.

## Command Parameters:

| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please select a variable to modify	| Select a variable (or enter text) which will contain the full string that needs to be extracted.   	|  **vSomeVariable** or text **HELLO**  	|  	|
|Start From Position|  Provide the index number of how many characters to pass before starting the selection  	| In this example, you could use **1** which would eliminate the leading **H** | 	|
|Optional - Length (-1 to keep remainder)   	| Input a -1 to keep everything after the Start position or enter how many characters to keep. |  **-1** would produce **ELLO**, **2** would produce **EL** 	|  	|
|Please select the variable to receive the changes | Select a variable (or enter text) which will contain the extracted text.    |  **vSomeVariable**   |   |

## Sample Task