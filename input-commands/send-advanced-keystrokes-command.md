<!--TITLE: Send Advanced Keystrokes Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Input Commands &gt; Send Advanced Keystrokes


# Send Advanced Keystrokes Command


## What does this command do?
Sends advanced keystrokes to a targeted window


## When would I want to use this command?
Use this command when you want to send advanced keystroke inputs to a window.


## Command Parameters
- [Please Enter the Window name (ex. Untitled - Notepad, Current Window, {vWindowName})](#param_0)
- [Optional - Window name search method (Default is Contains)](#param_1)
- [Set Keys and Parameters](#param_2)
- [Optional - Return all keys to 'UP' position after execution (Default is No)](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Enter the Window name (ex. Untitled - Notepad, Current Window, {vWindowName})


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to activate or bring forward.</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Sample Data</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindowName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window name search method (Default is Contains)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Contains</strong> or <strong>Starts with</strong> or <strong>Ends with</strong> or <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Set Keys and Parameters


<dl>
<dt>What to input</dt><dd>Define the parameters for the actions.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>Select Valid Options from the dropdowns</dd>
</dl>




<a id="param_3"></a>
### Optional - Return all keys to 'UP' position after execution (Default is No)


<dl>
<dt>What to input</dt><dd>Select either 'Yes' or 'No' as to a preference</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SendAdvancedKeyStrokesCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
