<!--TITLE: Wait For Folder To Exists Command -->
<!-- SUBTITLE: a command in the Folder Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Folder Operation Commands &gt; Wait For Folder To Exists


# Wait For Folder To Exists Command


## What does this command do?
This command waits for a folder to exist at a specified destination


## When would I want to use this command?
Use this command to wait for a folder to exist before proceeding.


## Command Parameters
- [Please indicate the path of the folder](#param_0)
- [Indicate how many seconds to wait for the file to exist](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please indicate the path of the folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the folder.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfolder or {vFolderPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Indicate how many seconds to wait for the file to exist


<dl>
<dt>What to input</dt><dd>Specify how long to wait before an error will occur because the folder is not found.</dd>
<dt>Sample Data</dt><dd>10 or 20 or {vWaitTime}</dd>
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
Automation Class Name: WaitForFolderToExistCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
