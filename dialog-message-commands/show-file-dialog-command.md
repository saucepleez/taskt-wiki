<!--TITLE: Show File Dialog Command -->
<!-- SUBTITLE: a command in the Dialog/Message Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dialog/Message Commands &gt; Show File Dialog


# Show File Dialog Command


## What does this command do?
Show OpenFileDialog or SaveFileDialog


## When would I want to use this command?
Use this command when you want to select file to save or open.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Select the Dialog Type](#param_0)
- [Optional - Please Specify the Value of the Filter Property](#param_1)
- [Optional - Please Specify the Value of the FilterIndex Property](#param_2)
- [Optional - Please Specify the Value of the InitialDirectory Property](#param_3)
- [Please Select the Variable Name to Store Result](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Optional - Please Select the Dialog Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Open</strong> or  <strong>Save</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Open</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Value of the Filter Property


<dl>
<dt>What to input</dt><dd>Enter or Select the Filter</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>All Files (<em>.</em>)|<em>.</em></strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Value of the FilterIndex Property


<dl>
<dt>What to input</dt><dd>Enter or Select the FilterIndex</dd>
<dt>Sample Usage</dt><dd>1 or 2 or {vIndex}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify the First Filter |
| <strong>2</strong> | Specify **2** for FilterIndex |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for FilterIndex |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Value of the InitialDirectory Property


<dl>
<dt>What to input</dt><dd>Enter or Select the InitialDirectory</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>C:\temp or {vFilePath} or C:\Users\myUser\Documents or {vFolderPath}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Documents</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp</strong> | Specify **C:\temp** for Folder Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for Folder Path |
| <strong>C:\Users\myUser\Documents</strong> | Specify **C:\Users\myUser\Documents** for InitialDirectory |
| <strong>{vFolderPath}</strong> | Specify Value of Variable **vFolderPath** for InitialDirectory |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
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
Automation Class Name: ShowFileDialogCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
