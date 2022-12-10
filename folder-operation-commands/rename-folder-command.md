<!--TITLE: Rename Folder Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Folder Operation Commands &gt; Rename Folder


# Rename Folder Command


## What does this command do?
This command renames a folder at a specified destination


## When would I want to use this command?
Use this command to rename an existing folder.


## Command Parameters
- [Please indicate the path to the source folder](#param_0)
- [Please indicate the new folder name](#param_1)
- [Optional - Please select If Folder Name Same After the Change](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the path to the source folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the folder.</dd>
<dt>Sample Data</dt><dd>C:\temp\myFolder or {vTextFolderPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the new folder name


<dl>
<dt>What to input</dt><dd>Specify the new folder name.</dd>
<dt>Sample Data</dt><dd>newFolderName or {vNewFolderName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please select If Folder Name Same After the Change


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Error</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RenameFolderCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
