<!--TITLE: Load Script File Command -->
<!-- SUBTITLE: a command in the Script File Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Script File Commands &gt; Load Script File


# Load Script File Command


## What does this command do?
This command pre-loads tasks for future execution.


## When would I want to use this command?
Use this command when you want to load a task but not immediately execute it.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Script File. After, Use 'Run Script File' with the Same Path to Execute.](#param_0)
- [Optional - Please Specify the Comment Field](#param_1)


<a id="param_0"></a>
### Please Specify the Script File. After, Use 'Run Script File' with the Same Path to Execute.


<dl>
<dt>What to input</dt><dd>Enter or Select the Script File</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myscript.xml</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myscript.xml</strong> | Specify **C:\temp\myscript.xml** for Script File |
| <strong>{vPath}</strong> | Specify Value of Variable **vPath** for Script File |


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
Automation Class Name: LoadScriptFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/21/23 01:49 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
