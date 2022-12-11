<!--TITLE: Wait For Window To Exist Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Window Commands &gt; Window Actions &gt; Wait For Window To Exist


# Wait For Window To Exist Command


## What does this command do?
This command waits for a window to exist.


## When would I want to use this command?
Use this command when you want to explicitly wait for a window to exist before continuing script execution.


## Command Parameters
- [Please enter or select the window name that you are waiting for to exist.](#param_0)
- [Optional - Window title search method](#param_1)
- [Indicate how many seconds to wait before an error should be raised.](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please enter or select the window name that you are waiting for to exist.


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window that you want to wait to exist.</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window title search method


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Contains</strong> or <strong>Starts with</strong> or <strong>Ends with</strong> or <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




<a id="param_2"></a>
### Indicate how many seconds to wait before an error should be raised.


<dl>
<dt>What to input</dt><dd>Specify how many seconds to wait before an error should be invoked</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>5</strong> or <strong>{vWaitTime}</strong></dd>
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
Automation Class Name: WaitForWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
