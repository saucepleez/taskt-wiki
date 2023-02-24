<!--TITLE: Get File Info Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Get File Info


# Get File Info Command


## What does this command do?
This command returns a list of file paths from a specified location


## When would I want to use this command?
Use this command to return a list of file paths from a specific location.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the file name](#param_0)
- [Please specify the information type.](#param_1)
- [Please Specify the variable to assign the result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please indicate the file name


<dl>
<dt>What to input</dt><dd>Enter or Select the file name.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vFileName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify the information type.


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>File size</strong> or  <strong>Readonly file</strong> or  <strong>Hidden file</strong> or  <strong>Creation time</strong> or  <strong>Last write time</strong> or  <strong>Last access time</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the variable to assign the result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetFileInfoCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/24/23 08:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
