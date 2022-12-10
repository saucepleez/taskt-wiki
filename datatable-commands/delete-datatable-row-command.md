<!--TITLE: Delete DataTable Row Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Row Action &gt; Delete DataTable Row


# Delete DataTable Row Command


## What does this command do?
This command allows you to delete a DataTable Row


## When would I want to use this command?
Use this command when you want to delete a DataTable Row.


## Command Parameters
- [Please indicate the DataTable Variable Name to be delete a row](#param_0)
- [Optional - Please specify the Row Index to delete](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name to be delete a row


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable Variable Name</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Row Index to delete


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or 1 or -1 or {vRow}</dd>
<dt>Remarks</dt><dd>-1 means index of the last row.<b>Optional</b><br>Default Value is Current Row</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: DeleteDataTableRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
