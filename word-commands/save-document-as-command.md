<!--TITLE: Save Document As Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Word Commands &gt; Save Document As


# Save Document As Command


## What does this command do?
This command allows you to save an Word document.


## When would I want to use this command?
Use this command when you want to save a document to a file.


<a id="param_list"></a>
## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please indicate the path of the file](#param_1)
- [Please Specify the Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Word</strong> command</dd>
<dt>Instance Type</dt><dd>Word</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Word</strong> command will cause an error.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please indicate the path of the file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the file.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If file does not contain extensin, supplement docx extension.
If file does not contain folder path, file will be saved in the same folder as script file.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WordSaveAsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
