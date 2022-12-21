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
- [Please indicate the path to the file](#param_0)
- [Please Select the Please define where the JSON should be stored](#param_1)
- [Please Specify the Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please indicate the path to the file


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


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Please define where the JSON should be stored


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ReadJSONFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
