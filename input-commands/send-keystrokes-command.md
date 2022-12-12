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
- [Optional - Please Select the Window name search method](#param_1)
- [Please Specify the Please Enter text to send.](#param_2)
- [Optional - Please Select the Please Indicate if Text is Encrypted](#param_3)
- [Optional - Please Specify the Please specify waiting time after keystrokes (ms)](#param_4)
- [Please Specify the Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the Window name


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Sample Usage</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindowName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Select the Window name search method


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Contains</strong> or  <strong>Starts with</strong> or  <strong>Ends with</strong> or  <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




<a id="param_2"></a>
### Please Specify the Please Enter text to send.


<dl>
<dt>What to input</dt><dd>Enter the text that should be sent to the specified window.</dd>
<dt>Sample Usage</dt><dd><strong>Hello, World!</strong> or <strong>^s</strong> or <strong>{vEntryText}</strong> or <strong>{WIN_KEY}</strong> or <strong>{WIN_KEY+R}</strong></dd>
<dt>Remarks</dt><dd>This command supports sending variables within brackets {{{vVariable}}}</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Select the Please Indicate if Text is Encrypted


<dl>
<dt>What to input</dt><dd>Indicate if the text in 'TextToSend' is Encrypted.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Not Encrypted</strong> or  <strong>Encrypted</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Not Encrypted</strong></dd>
</dl>




<a id="param_4"></a>
### Optional - Please Specify the Please specify waiting time after keystrokes (ms)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If less than 100 is specified, it will be 100<br><br>
<strong>Optional</strong><br>Default Value is <strong>500</strong></dd>
</dl>




<a id="param_5"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendKeysCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
