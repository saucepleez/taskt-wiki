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
- [Optional - Please Specify the Comment Field](#param_1)


<a id="param_0"></a>
### Please Specify the Path to the Batch Script File


<dl>
<dt>What to input</dt><dd>Enter or Select the Path</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myscript.bat</strong> or <strong>C:\temp\myscript.vbs</strong> or <strong>C:\temp\myscript.js</strong> or <strong>{vScriptPath}</strong></dd>
<dt>Remarks</dt><dd>This command differs from <strong>Start Process</strong> because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using <strong>Start Process</strong> instead.
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
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: RunBatchScriptFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/26/23 01:37 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
