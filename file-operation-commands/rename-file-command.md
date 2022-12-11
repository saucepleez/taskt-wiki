<!--TITLE: Rename File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Rename File


# Rename File Command


## What does this command do?
This command renames a file at a specified destination


## When would I want to use this command?
Use this command to rename an existing file.


## Command Parameters
- [Please indicate the path to the source file](#param_0)
- [Please indicate the new file name (with extension)](#param_1)
- [Optional - Please select If File Name Same After the Change](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the path to the source file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the new file name (with extension)


<dl>
<dt>What to input</dt><dd>Specify the new file name including the extension.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>newfile.txt</strong> or <strong>{vNewFileName}</strong></dd>
<dt>Remarks</dt><dd>Changing the file extension will not automatically convert files.</dd>
</dl>




<a id="param_2"></a>
### Optional - Please select If File Name Same After the Change


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Ignore</strong> or <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RenameFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
