<!--TITLE: Convert DataTable Row To JSON Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Convert Row &gt; Convert DataTable Row To JSON


# Convert DataTable Row To JSON Command


## What does this command do?
This command allows you to convert DataTable Row to JSON


## When would I want to use this command?
Use this command when you want to convert DataTable Row to JSON.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please enter the index of the Row](#param_1)
- [Please Specify the Variable Name To Assign The JSON](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable to fet rows from.</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please enter the index of the Row


<dl>
<dt>What to input</dt><dd>Enter a valid DataRow index value</dd>
<dt>Sample Data</dt><dd>0 or 1 or -1 or {vRowIndex}</dd>
<dt>Remarks</dt><dd>-1 means index of the last row.<b>Optional</b><br>Default Value is Current Row</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Variable Name To Assign The JSON


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertDataTableRowToJSONCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
