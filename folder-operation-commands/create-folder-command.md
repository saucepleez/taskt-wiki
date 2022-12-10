<!--TITLE: Create Folder Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Folder Operation Commands &gt; Create Folder


# Create Folder Command


## What does this command do?
This command creates a folder in a specified destination


## When would I want to use this command?
Use this command to create a folder in a specific location.


## Command Parameters
- [Please indicate the name of the new folder](#param_0)
- [Please indicate the directory for the new folder](#param_1)
- [Optional - Delete folder if it already exists](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the name of the new folder


<dl>
<dt>What to input</dt><dd>Enter the name of the new folder.</dd>
<dt>Sample Data</dt><dd>myFolderName or {vFolderName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the directory for the new folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the directory.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfolder or {TextFolderPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Delete folder if it already exists


<dl>
<dt>What to input</dt><dd>Specify whether the folder should be deleted first if it is already found to exist.</dd>
<dt>Sample Data</dt><dd>Select Yes or No</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is No</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CreateFolderCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
