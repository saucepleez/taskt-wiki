<!--TITLE: Write Text File Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; File &gt; Write Text File


# Write Text File Command


## What does this command do?
This command writes specified data to a text file


## When would I want to use this command?
Use this command when you want to write data to text files.


## Command Parameters
- [Please indicate the path to the file](#param_0)
- [Please indicate the text to be written. [crLF] inserts a newline.](#param_1)
- [Optional - Please select overwrite option](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the path to the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the text file.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement txt automatically.
If file does not contain folder path, file will be saved in the same folder as script file.
If file path contains FileCounter variable, it will be replaced by a number that will become the name of a non-existent file.</dd>
</dl>




<a id="param_1"></a>
### Please indicate the text to be written. [crLF] inserts a newline.


<dl>
<dt>What to input</dt><dd>Indicate the text should be written to files.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>{vText}</strong> or <strong>Hello World!</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please select overwrite option


<dl>
<dt>What to input</dt><dd>Indicate whether this command should append the text to or overwrite all existing text in the file</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select from <strong>Append</strong> or <strong>Overwrite</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Overwrite</strong></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WriteTextFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
