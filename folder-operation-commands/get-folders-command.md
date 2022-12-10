<!--TITLE: Get Folders Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Folder Operation Commands &gt; Get Folders


# Get Folders Command


## What does this command do?
This command returns a list of folder directories from a specified location


## When would I want to use this command?
Use this command to return a list of folder directories from a specific location.


## Command Parameters
- [Please indicate the path to the source folder](#param_0)
- [Optional - Please indicate the folder name filter](#param_1)
- [Optional - Please indicate the file name search method](#param_2)
- [Specify the variable to assign the folder path list](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please indicate the path to the source folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the folder.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfolder or {vTextFolderPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please indicate the folder name filter


<dl>
<dt>What to input</dt><dd>Enter or Select the folder name filter.</dd>
<dt>Sample Data</dt><dd>hello or {vFolderName}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is  empty and searched all folders</dd>
</dl>




<a id="param_2"></a>
### Optional - Please indicate the file name search method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Contains</dd>
</dl>




<a id="param_3"></a>
### Specify the variable to assign the folder path list


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetFoldersCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
