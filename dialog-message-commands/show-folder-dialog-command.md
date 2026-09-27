<!--TITLE: Show Folder Dialog Command -->
<!-- SUBTITLE: a command in the Dialog/Message group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dialog/Message &gt; Show Folder Dialog


# Show Folder Dialog Command


## What does this command do?
Show FolderBrowserDialog


## When would I want to use this command?
Use this command when you want to select folder.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Select the Dialog Type](#param_0)
- [Optional - Please Specify the Initial Folder Path](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Select the When Dialog Result Is Cancel](#param_3)
- [Please Select the Variable Name To Store Dislog Result](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Optional - Please Select the Dialog Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>FolderBrowserDialog</strong> or  <strong>CommonOpenFolderDialog</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>CommonOpenFolderDialog</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Initial Folder Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Initial Folder Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>C:\Users\myUser\Documents or {vFolderPath} or C:\temp or {vFilePath}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Documents</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\Users\myUser\Documents</strong> | Specify **C:\Users\myUser\Documents** for Initial Folder Path |
| <strong>{vFolderPath}</strong> | Specify Value of Variable **vFolderPath** for Initial Folder Path |
| <strong>C:\temp</strong> | Specify **C:\temp** for Folder Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for Folder Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When Dialog Result Is Cancel


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Set Empty</strong> or  <strong>Show Dialog Again</strong> or  <strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Show Dialog Again</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing to do. The Result Variable is not Changed. |
| <strong>Set Empty</strong> | Result Variable value is Empty |
| **Show Dialog Again | Show Dialog Again |
| <strong>Ignore</strong> | Nothing To Do |
| <strong>Error</strong> | Rise an Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
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


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ShowFolderDialogCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
