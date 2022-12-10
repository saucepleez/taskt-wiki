<!--TITLE: Start Process Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Programs/Process Commands &gt; Start Process


# Start Process Command


## What does this command do?
This command allows you to start a program or a process.


## When would I want to use this command?
Use this command to start applications by entering their name such as 'chrome.exe' or a fully qualified path to a file 'c:/some.exe'


## Command Parameters
- [Please enter the name or path to the program (ex. notepad, calc, C:\temp\myapp.exe, {vPath})](#param_0)
- [Optional - Please enter any arguments (ex. -a, -version, {vArgs})](#param_1)
- [Optional - Wait for the process to complete? (Default is No)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please enter the name or path to the program (ex. notepad, calc, C:\temp\myapp.exe, {vPath})


<dl>
<dt>What to input</dt><dd>Provide a valid program name or enter a full path to the script/executable including the extension.
If file does not contain folder path, this command do not supplement folder path.</dd>
<dt>Sample Data</dt><dd>notepad or calc or c:\temp\myapp.exe or {vPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please enter any arguments (ex. -a, -version, {vArgs})


<dl>
<dt>What to input</dt><dd>Enter any arguments or flags if applicable.</dd>
<dt>Sample Data</dt><dd>-a or -version or {vArgs}</dd>
<dt>Remarks</dt><dd>You will need to consult documentation to determine if your executable supports arguments or flags on startup.</dd>
</dl>




<a id="param_2"></a>
### Optional - Wait for the process to complete? (Default is No)


<dl>
<dt>What to input</dt><dd>Wait For Exit.</dd>
<dt>Sample Data</dt><dd>Select Yes or No</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: StartProcessCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
