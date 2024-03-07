<!--TITLE: Delete Folder Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Folder Operation Commands &gt; Delete Folder


# Delete Folder Command


## What does this command do?
This command deletes a folder from a specified destination


## When would I want to use this command?
Use this command to delete a folder from a specific location.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Folder Path](#param_0)
- [Optional - Please Select the Folder Move to the Recycle Bin](#param_1)
- [Optional - Please Specify the Wait Time for the Folder to Exist (sec)](#param_2)
- [Optional - Please Select the Variable Name to Store Folder Path](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the Folder Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Folder Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>C:\temp or {vFilePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp</strong> | Specify **C:\temp** for Folder Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for Folder Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the Folder Move to the Recycle Bin


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Wait Time for the Folder to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Folder is not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Variable Name to Store Folder Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vPath or {vPath}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vPath</strong> | Specify Variable Name **vPath** |
| <strong>{vPath}</strong> | Specify Variable Name **vPath** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: DeleteFolderCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/07/24 09:15 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
