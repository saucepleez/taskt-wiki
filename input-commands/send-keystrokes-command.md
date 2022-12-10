<!--TITLE: Send Keystrokes Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Input Commands &gt; Send Keystrokes


# Send Keystrokes Command


## What does this command do?
Sends keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send keystroke inputs to a window.


## Command Parameters
- [Please Enter the Window name](#param_0)
- [Optional - Window name search method](#param_1)
- [Please Enter text to send.](#param_2)
- [Optional - Please Indicate if Text is Encrypted](#param_3)
- [Optional - Please specify waiting time after keystrokes (ms)](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the Window name


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Sample Data</dt><dd>Untitled - Notepad or Current Window or {vWindowName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window name search method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Contains</dd>
</dl>




<a id="param_2"></a>
### Please Enter text to send.


<dl>
<dt>What to input</dt><dd>Enter the text that should be sent to the specified window.</dd>
<dt>Sample Data</dt><dd>Hello, World! or ^s or {vEntryText} or {WIN_KEY} or {WIN_KEY+R}</dd>
<dt>Remarks</dt><dd>This command supports sending variables within brackets {vVariable}</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Indicate if Text is Encrypted


<dl>
<dt>What to input</dt><dd>Indicate if the text in 'TextToSend' is Encrypted.</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Not Encrypted</dd>
</dl>




<a id="param_4"></a>
### Optional - Please specify waiting time after keystrokes (ms)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>500 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>If less than 100 is specified, it will be 100<b>Optional</b><br>Default Value is 500</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendKeysCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
