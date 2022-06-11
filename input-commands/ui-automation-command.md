<!--TITLE: UI Automation Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


# UI Automation Command


## What does this command do?
Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.


## When would I want to use this command?
Data not specified


## Command Parameters
| Parameter Question   	| What to input  	|  Sample Data 	| Remarks  	|
| ---                    | ---               | ---           | ---       |
|Please indicate the action|Data not specified|**Click Element** or **Get Value From Element** or **Check If Element Exists** or **Get Text Value From Element** or **Get Check State From Element**||
|Please select the Window to Automate (ex. Untitled - Notepad, Current Window, {vWindowName}}|Input or Type the name of the window that you want to activate or bring forward.|**Untitled - Notepad** or **Current Window** or **{vWindowName}**||
|Optional - Window name search method (Default is Contains)||**Contains** or **Starts with** or **Ends with** or **Exact match**||
|Set Search Parameters|Use the Element Recorder to generate a listing of potential search parameters.|n/a|Once you have clicked on a valid window the search parameters will be populated.  Enable only the ones required to be a match at runtime.|
|Set Action Parameters|Define the parameters for the actions.|n/a|Parameters change depending on the Automation Type selected.|
|Comment Field (Optional)|Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required|I am using this command to ...|Optional|














## Developer/Additional Reference
Automation Class Name: UIAutomationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 06/11/22 06:53 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
