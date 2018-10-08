<!-- TITLE: Set Variable Command -->
# Set Variable Command
![Set Variable](/uploads/automation-commands/set-variable.png "Set Variable")
## What does this command do?
This is a commonly used command which lets you manually specify the value of variables within taskt.
## When would I use this command?
Use this command any time that you want to set a variable's value.  Variables have a wide range of uses which allow you to dynamically assign and use values in your scripts.  [Learn more about variables.](/concepts/variables)

## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Please select a variable to modfy	| Select a variable which will be targeted for assignment.   	|  **vSomeExistingVariable**  	|  If your variable does not exist, you can create one from the 'Variables' button in the action bar.   If you have 'Create Missing Variables During Execution' enabled, you can simply type the name of the variable and it will be created during the task execution.	|
|Please define the input to be set to above variable 	|  Define what value the variable should contain. 	| You can input text like **Hello** or even other variables like **[vTextLength]**  	|  Make sure to wrap any variables within quotes 	|

## Sample Task