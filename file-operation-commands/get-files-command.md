<!--TITLE: Get Files Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
File Operation Commands &gt; Get Files


# Get Files Command


## What does this command do?
This command returns a list of file paths from a specified location


## When would I want to use this command?
Use this command to return a list of file paths from a specific location.


## Command Parameters
- [Please indicate the path to the source folder.](#param_0)
- [Optional - Please indicate the file name filter](#param_1)
- [Optional - Please indicate the file name search method](#param_2)
- [Optional - Please indicate the extension](#param_3)
- [Specify the variable to assign the file path list](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please indicate the path to the source folder.


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the folder.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfolder or {vTextFolderPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please indicate the file name filter


<dl>
<dt>What to input</dt><dd>Enter or Select the file name filter.</dd>
<dt>Sample Data</dt><dd>hello or {vFileName}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is empty and search all files</dd>
</dl>




<a id="param_2"></a>
### Optional - Please indicate the file name search method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Contains</dd>
</dl>




<a id="param_3"></a>
### Optional - Please indicate the extension


<dl>
<dt>What to input</dt><dd>Enter or Select the extension.</dd>
<dt>Sample Data</dt><dd>txt or {vExtension}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is empty and search all files</dd>
</dl>




<a id="param_4"></a>
### Specify the variable to assign the file path list


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetFilesCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
