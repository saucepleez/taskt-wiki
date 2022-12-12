<!--TITLE: Format File Path Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Format File Path


# Format File Path Command


## What does this command do?
This command allows you to format file path.


## When would I want to use this command?
Use this command when you want to format file path.


## Command Parameters
- [Please indicate the File Path to Delete.](#param_0)
- [Please Select the Please specify File Path Format.](#param_1)
- [Please Select the Please specify Variable Name to store Result.](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the File Path to Delete.


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select the Please specify File Path Format.


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>FileName</strong> or  <strong>FileNameWithoutExtension</strong> or  <strong>Folder</strong> or  <strong>Extension</strong> or  <strong>DriveName</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Select the Please specify Variable Name to store Result.


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: FormatFilePathCommnad
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)