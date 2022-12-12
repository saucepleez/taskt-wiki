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
- [Optional - Please Select the Window name search method (Default is Contains)](#param_1)
- [Please Select the Please select Hotkey to Send.](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the Window name


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Sample Usage</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindowName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Select the Window name search method (Default is Contains)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Contains</strong> or  <strong>Starts with</strong> or  <strong>Ends with</strong> or  <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Please Select the Please select Hotkey to Send.


<dl>
<dt>What to input</dt><dd>Enter the text that should be sent to the specified window.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>New</strong> or  <strong>New Window</strong> or  <strong>Open</strong> or  <strong>Print</strong> or  <strong>Save</strong> or  <strong>Save As</strong> or  <strong>Undo</strong> or  <strong>Cut</strong> or  <strong>Copy</strong> or  <strong>Paste</strong> or  <strong>Delete</strong> or  <strong>Search</strong> or  <strong>Find</strong> or  <strong>Find Next</strong> or  <strong>Find Previous</strong> or  <strong>Replace</strong> or  <strong>Go To</strong> or  <strong>Select All</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>


#### Addtional Info about &quot;Please Select the Please select Hotkey to Send.&quot;
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
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendHotkeyCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
