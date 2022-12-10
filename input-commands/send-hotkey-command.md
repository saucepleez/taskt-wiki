<!--TITLE: Send Hotkey Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Input Commands &gt; Send Hotkey


# Send Hotkey Command


## What does this command do?
Sends keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send keystroke inputs to a window.


## Command Parameters
- [Please Enter the Window name](#param_0)
- [Optional - Window name search method (Default is Contains)](#param_1)
- [Please select Hotkey to Send.](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the Window name


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Sample Data</dt><dd>Untitled - Notepad or Current Window or {vWindowName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window name search method (Default is Contains)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Please select Hotkey to Send.


<dl>
<dt>What to input</dt><dd>Enter the text that should be sent to the specified window.</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>


### Addtional Info about &quot;Please select Hotkey to Send.&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|New|Send Ctrl + N|||
|New Window|Send Ctrl + Shift + N|||
|Open|Send Ctrl + O|||
|Print|Send Ctrl + P|||
|Save|Send Ctrl + S|||
|Save As|Send Ctrl + Shift + S|||
|Undo|Send Ctrl + Z|||
|Cut|Send Ctrl + X|||
|Copy|Send Ctrl + C|||
|Paste|Send Ctrl + V|||
|Delete|Send Delete|||
|Search|Send Ctrl + E|||
|Find|Send Ctrl + F|||
|Find Next|Send F3|||
|Find Previous|Send Shift + F3|||
|Replace|Send Ctrl + H|||
|Go To|Send Ctrl + G|||
|Select All|Send Ctrl + A|||


<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendHotkeyCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
