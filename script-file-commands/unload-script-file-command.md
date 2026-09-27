<!--TITLE: Unload Script File Command -->
<!-- SUBTITLE: a command in the Script File Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Script File Commands &gt; Unload Script File


# Unload Script File Command


## What does this command do?
This command runs tasks.


## When would I want to use this command?
Use this command when you want to run another task.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Script File to Pre-Load. Use 'Run Script File' with the same path to execute.](#param_0)
- [Optional - Please Select the Unload Error Preference](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Specify the Script File to Pre-Load. Use 'Run Script File' with the same path to execute.


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
### Optional - Please Select the Unload Error Preference


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error if not found</strong> or  <strong>Continue if not found</strong></dd>
<dt>Remarks</dt><dd>Selecting this field changes the parameters that will be required in the next step<br><br>
<strong>Optional</strong><br>Default Value is <strong>Continue if not found</strong></dd>
</dl>




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
Automation Class Name: UnloadScriptFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/21/23 01:49 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
