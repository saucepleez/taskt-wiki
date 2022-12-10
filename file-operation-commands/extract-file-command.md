<!--TITLE: Extract File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
File Operation Commands &gt; Extract File


# Extract File Command


## What does this command do?
This command extracts files from a compressed file


## When would I want to use this command?



## Command Parameters
- [Please enter the file path or location](#param_0)
- [Please indicate the extraction folder](#param_1)
- [Optional - Create folder if destination does not exist](#param_2)
- [Optional - Indicate the archive password](#param_3)
- [Optional - Indicate the variable to receive a list of extracted file names](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please enter the file path or location


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file or enter file URL.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.zip , {vFilePath} or https://temp.com/myfile.zip</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the extraction folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file or enter file URL.</dd>
<dt>Sample Data</dt><dd>C:\temp* or {vFilePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Create folder if destination does not exist


<dl>
<dt>What to input</dt><dd>Specify whether the directory should be created if it does not already exist.</dd>
<dt>Sample Data</dt><dd>Select Yes or No</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is No</dd>
</dl>




<a id="param_3"></a>
### Optional - Indicate the archive password


<dl>
<dt>What to input</dt><dd>Enter archive files password.</dd>
<dt>Sample Data</dt><dd>mypass or {vPass}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Indicate the variable to receive a list of extracted file names


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.<b>Optional</b><br></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExtractFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
