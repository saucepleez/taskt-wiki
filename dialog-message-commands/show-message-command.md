<!--TITLE: Show Message Command -->
<!-- SUBTITLE: a command in the Dialog/Message group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dialog/Message &gt; Show Message


# Show Message Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Message to be Displayed](#param_0)
- [Optional - Please Specify the Close After X (Seconds) - 0 to Bypass](#param_1)
- [Optional - Please Specify the Font Name](#param_2)
- [Optional - Please Specify the Font Size](#param_3)
- [Optional - Please Select the Dialog Type](#param_4)
- [Optional - Please Specify the Dialog Title](#param_5)
- [Optional - Please Select the Wait for answer](#param_6)
- [Please Select the Variable Name To Store Dislog Result](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Specify the Message to be Displayed


<dl>
<dt>What to input</dt><dd>Enter or Select the Message</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>Hello World or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello World</strong> | Specify **Hello World** for Message |
| <strong>{vText}</strong> | Specify Value of Variable **vText** for Message |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Close After X (Seconds) - 0 to Bypass


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or 0 or {vTime}</dd>
<dt>Remarks</dt><dd>Specify how many seconds to display on screen.After the amount of seconds passes, the message box will be automatically closed and script will resume execution. <strong>0</strong> to remain open indefinitely or <strong>5</strong> to stay open for 5 seconds.<br><br>
<strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Close After 1 second |
| <strong>0</strong> | Don't Close Automatically |
| <strong>{vTime}</strong> | Close After Value of Variable **vTime** seconds |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Font Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>MS Gothic</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>MS Gothic</strong> | Specify MS Gothic |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Font Size


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>12 or {vFont}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>12</strong> | Specify **12** for Font Size |
| <strong>{vFont}</strong> | Specify Variable Name **vFont** for Font Size |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Dialog Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>OkOnly</strong> or  <strong>YesNo</strong> or  <strong>OkCancel</strong> or  <strong>Close</strong> or  <strong>Nothing</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>OkOnly</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Dialog Title


<dl>
<dt>What to input</dt><dd>Enter or Select the Title</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>Title or {vTitle}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>ShowMessage Command</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Title</strong> | Specify **Title** |
| <strong>{vTitle}</strong> | Specify Value of Variable **vTitle** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Wait for answer


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Yes</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Please Select the Variable Name To Store Dislog Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>Value is <strong>OK</strong> or <strong>Cancel</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ShowMessageCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
