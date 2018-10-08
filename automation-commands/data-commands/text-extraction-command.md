<!-- TITLE: Text Extraction Command -->
# Text Extraction Command

## What does this command do?
This command allows you to extract specific text from a larger piece of text

## When would I use this command?
Use this command when you want to extract text before, after, or between a certain occurence of a word or words.

## Command Parameters:

| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
|---					|---				|---			|---		|
|Supply the value or variable requiring extraction | Select a variable (or enter text) which will contain the full string that needs to be extracted.   	|  **vSomeVariable** or text **Hello from taskt**  	|  	|
|Please select the extraction type|  Provide the type of extraction required 	| Choose from **Extract All Before Text**, **Extract All After Text**, **Extract All Between Text** |  	|
|Extraction Parameters   	| Specify the parameters based on extraction type.   **Extract All After Text** requires a leading occurence and how many occurences to skip past.  **Extract All Before Text** requires a trailing occurence and how many occurences to skip past. **Extract All Between Text** requires a leading **and** trailing occurence and how many occurences to skip past.  Leading Occurence is the leading text, everything after that leading text will be parsed.  Trailing Occurence is the trailing text, everything before the trailing text will be parsed.  |  Selecting **Extract All Before Text** and specifying **taskt!** as trailing occurence would produce result **Hello from**, Selecting **Extract All After Text** and specifying **Hello** as leading occurence would produce result **from taskt!** , Selecting **Extract All Between Text** and specifying **Hello!** as leading occurence and **taskt!** as trailing occurence would produce result **from**   	|  	|
|Please select the variable to receive the extracted text | Select a variable (or enter text) which will contain the extracted text.    |  **vSomeVariable**   |   |


## Sample Task