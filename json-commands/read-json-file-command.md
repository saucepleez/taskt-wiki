<!--TITLE: Read JSON File Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; File &gt; Read JSON File


# Read JSON File Command


## What does this command do?
This command reads JSON data into a variable


## When would I want to use this command?
Use this command when you want to read data from JSON files.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Path to the File](#param_0)
- [Please Select the JSON Variable Name](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Specify the Path to the File


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the text file.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong> or <strong>http://example.com/api/</strong> or <strong>{vURL}</strong></dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement txt automatically.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the JSON Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON <strong>Variable Name</strong></dd>
<dt>Value</dt><dd>JSON Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vJSON</strong> or <strong>{vJSON}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vJSON</strong> | Specify Variable Name **vJSON** |
| <strong>{vJSON}</strong> | Specify Variable Name **vJSON** |


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
Automation Class Name: ReadJSONFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/04/23 01:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
