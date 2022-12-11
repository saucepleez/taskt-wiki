<!--TITLE: Check File Exists Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Check File Exists


# Check File Exists Command


## What does this command do?
This command returns a existence of file paths from a specified location


## When would I want to use this command?
Use this command to return a existence of file paths from a specific location.


## Command Parameters
- [Specify the path of the file you want to check for existence](#param_0)
- [Specify the variable to assign the result](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Specify the path of the file you want to check for existence


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Specify the variable to assign the result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>Boolean</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>Result is <strong>TRUE</strong> or <strong>FALSE</strong></dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CheckFileExistsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
