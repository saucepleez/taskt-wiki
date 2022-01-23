<!--TITLE: Element Action Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# Element Action Command


## What does this command do?
This command allows you to close a Selenium web browser session.


## When would I want to use this command?
Use this command when you want to manipulate, set, or get data on a webpage within the web browser.


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please Enter the instance name|Enter the unique instance name that was specified in the **Create Browser** command|**myInstance** or **{vInstance}**|Failure to enter the correct instance name or failure to first call **Create Browser** command will cause an error|
|Element Search Method|Select the specific search type that you want to use to isolate the element in the web page.|Select **Find Element By XPath**, **Find Element By ID**, **Find Element By Name**, **Find Element By Tag Name**, **Find Element By Class Name**, **Find Element By CSS Selector**, **Find Element By Link Text**||
|Element Search Parameter|Specifies the parameter text that matches to the element based on the previously selected search type.|If search type **Find Element By ID** was specified, for example, given <div id='name'></div>, the value of this field would be **name**||
|Target Element Index (Only Use Fined Elements \*\*\*)||**0** or **1** or **{vIndex}**|If parameter is $x('//div') and index is 5, it's means target is $x('//div')[5].|
|Element Action|Select the appropriate corresponding action to take once the element has been located|Select from **Invoke Click**, **Left Click**, **Right Click**, **Middle Click**, **Double Left Click**, **Clear Element**, **Set Text**, **Get Text**, **Get Attribute**, **Wait For Element To Exist**, **Get Count**|Selecting this field changes the parameters that will be required in the next step|
|Additional Parameters|Additioal Parameters will be required based on the action settings selected.|Additional Parameters range from adding offset coordinates to specifying a variable to apply element text to.||
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|
















## Developer/Additional Reference
Automation Class Name: SeleniumBrowserElementActionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 01/23/22 09:09 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
