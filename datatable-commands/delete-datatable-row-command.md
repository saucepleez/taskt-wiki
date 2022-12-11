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
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDataTable</strong> or <strong>{vMyDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Row Index to delete


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>-1</strong> or <strong>{vRow}</strong></dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Row</strong></dd>
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
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
