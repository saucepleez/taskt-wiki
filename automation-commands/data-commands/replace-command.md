<!-- TITLE: Replace Command -->
# Replace Command

![Replace](/uploads/automation-commands/replace.png "Replace")

## What does this command do?
This command allows you to replace text within a variable (or string) with new text and apply to a user-specified variable.  [Learn more about variables.](/concepts/variables)

## When would I use this command?
Use this command when you want to replace some text within existing text.

## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please select text or variable to modify	| Select a variable (or enter text) which will contain the value of that is required to be replaced.   	|  **vSomeVariable** or text **Hello!**  	|  	|
|Indicate the text to be replaced   	|  Provide the text that will be found in the value  	| If the variable contained **Hello!**, provide **H** to replace the H	| 	|
|Indicate the replacement value  	|  Provide the text that will replace the existing text	| You could specify **J** which would replace the text to become **Jello!**   	|   	|
|Please select the variable to receive the changes  	|  Select a variable which will contain the value of the replaced text.  	| vDestinationVariable  	| If you have 'Create Missing Variables During Execution' enabled, you can simply type the name of the variable and it will be created during the task execution.  	|

## Sample Task