<!--TITLE: Wait For File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Wait For File


# Wait For File Command


## What does this command do?
This command waits for a file to exist at a specified destination


## When would I want to use this command?
Use this command to wait for a file to exist before proceeding.


## Command Parameters
- [Please indicate the directory of the file](#param_0)
- [Indicate how many seconds to wait for the file to exist](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please indicate the directory of the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vTextFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Indicate how many seconds to wait for the file to exist


<dl>
<dt>What to input</dt><dd>Specify how long to wait before an error will occur because the file is not found.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>10</strong> or <strong>20</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WaitForFileToExistCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
