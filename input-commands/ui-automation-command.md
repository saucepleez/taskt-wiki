<!--TITLE: UI Automation Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Input Commands &gt; UI Automation


# UI Automation Command


## What does this command do?
Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.


## When would I want to use this command?



## Command Parameters
- [Please indicate the action](#param_0)
- [Please select the Window to Automate (ex. Untitled - Notepad, Current Window, {vWindowName}}](#param_1)
- [Optional - Window name search method (Default is Contains)](#param_2)
- [Set Search Parameters](#param_3)
- [Set Action Parameters](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please indicate the action


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>Click Element or Get Value From Element or Check If Element Exists or Get Text Value From Element or Get Check State From Element</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the Window to Automate (ex. Untitled - Notepad, Current Window, {vWindowName}}


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Sample Data</dt><dd>Untitled - Notepad or Current Window or {vWindowName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Window name search method (Default is Contains)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Set Search Parameters


<dl>
<dt>What to input</dt><dd>Use the Element Recorder to generate a listing of potential search parameters.</dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>Once you have clicked on a valid window the search parameters will be populated.  Enable only the ones required to be a match at runtime.</dd>
</dl>




<a id="param_4"></a>
### Set Action Parameters


<dl>
<dt>What to input</dt><dd>Define the parameters for the actions.</dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>Parameters change depending on the Automation Type selected.</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: UIAutomationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
