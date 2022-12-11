<!--TITLE: Move/Copy File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Move/Copy File


# Move/Copy File Command


## What does this command do?
This command moves a file to a specified destination


## When would I want to use this command?
Use this command to move a file to a new destination.


## Command Parameters
- [Optional - Indicate whether to move or copy the file](#param_0)
- [Please indicate the path to the source file](#param_1)
- [Please indicate the directory to move/copy to](#param_2)
- [Optional - Create folder if destination does not exist](#param_3)
- [Optional - Delete file if it already exists](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Optional - Indicate whether to move or copy the file


<dl>
<dt>What to input</dt><dd>Specify whether you intend to move the file or copy the file.  Moving will remove the file from the original path while Copying will not.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select either <strong>Move File</strong> or <strong>Copy File</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Move File</strong></dd>
</dl>




<a id="param_1"></a>
### Please indicate the path to the source file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please indicate the directory to move/copy to


<dl>
<dt>What to input</dt><dd>Enter or Select the new path to the file.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>*<em>C:\temp\new path*</em> or <strong>{vTextFolderPath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Create folder if destination does not exist


<dl>
<dt>What to input</dt><dd>Specify whether the directory should be created if it does not already exist.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<a id="param_4"></a>
### Optional - Delete file if it already exists


<dl>
<dt>What to input</dt><dd>Specify whether the file should be deleted first if it is already found to exist.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MoveFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
