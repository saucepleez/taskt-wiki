<!--TITLE: Read Text File Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; File &gt; Read Text File


# Read Text File Command


## What does this command do?
This command allows you to read text file into a variable


## When would I want to use this command?
Use this command when you want to read data from text files.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the path to the file](#param_0)
- [Optional - Please select the read type](#param_1)
- [Please Specify Variable the text should be stored](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please indicate the path to the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the text file.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong> or <strong>http://example.com/mytext.txt</strong> or <strong>{vURL}</strong></dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement txt automatically.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please select the read type


<dl>
<dt>What to input</dt><dd>Select the appropriate window state required</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Content</strong> or  <strong>Line Count</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Content</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify Variable the text should be stored


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vTextFile</strong> or <strong>{vTextFile}</strong></dd>
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
Automation Class Name: ReadTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/04/23 01:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
