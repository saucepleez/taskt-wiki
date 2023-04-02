<!--TITLE: Run Batch Script File Command -->
<!-- SUBTITLE: a command in the Application/Script Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Application/Script Commands &gt; Windows Script File &gt; Run Batch Script File


# Run Batch Script File Command


## What does this command do?
This command allows you to run a script or program and wait for it to exit before proceeding.


## When would I want to use this command?
Use this command when you want to run a script (such as vbScript, javascript, or executable) but wait for it to close before taskt continues executing.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Path to the Batch Script File](#param_0)
- [Optional - Please Specify the Wait Time for the File to Exist (sec)](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Specify the Path to the Batch Script File


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance Required</li><li>Support Extensions: bat,vbs,js,wsh</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myscript.bat</strong> or <strong>C:\temp\myscript.vbs</strong> or <strong>C:\temp\myscript.js</strong> or <strong>{vScriptPath}</strong></dd>
<dt>Remarks</dt><dd>This command differs from <strong>Start Application</strong> because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using <strong>Start Application</strong> instead.
If file does not contain extensin, supplement ps1 or bat extension.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myscript.bat</strong> | Specify **C:\temp\myscript.bat** for Script File |
| <strong>C:\temp\myscript.vbs</strong> | Specify **C:\temp\myscript.vbs** for Script File |
| <strong>C:\temp\myscript.js</strong> | Specify **C:\temp\myscript.js** for Script File |
| <strong>{vScriptPath}</strong> | Specify Value of Variable **vScriptPath** for Script File |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Wait Time for the File to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>10</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the File is not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: RunBatchScriptFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
