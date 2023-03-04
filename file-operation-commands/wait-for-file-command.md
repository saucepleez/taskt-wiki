<!--TITLE: Wait For File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Wait For File


# Wait For File Command


## What does this command do?
This command waits for a file to exist at a specified destination


## When would I want to use this command?
Use this command to wait for a file to exist before proceeding.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the directory of the file](#param_0)
- [Please Indicate how many seconds to wait for the file to exist](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please indicate the directory of the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Indicate how many seconds to wait for the file to exist


<dl>
<dt>What to input</dt><dd>Specify how long to wait before an error will occur because the file is not found.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>10</strong> or <strong>20</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
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
Automation Class Name: WaitForFileToExistCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/04/23 01:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
