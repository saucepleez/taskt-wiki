<!--TITLE: Get DataTable Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; DataTable Action &gt; Get DataTable Value


# Get DataTable Value Command


## What does this command do?
This command allows you to get the DataTable value


## When would I want to use this command?
Use this command when you want to get the DataTable value.


## Command Parameters
- [Please indicate the DataTable Variable Name](#param_0)
- [Optional - Please specify the Column value type](#param_1)
- [Please specify the Column Name or Index](#param_2)
- [Optional - Please specify the Row Index](#param_3)
- [Please Specify the Variable Name To Assign the Value](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable.</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Column value type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Index or Column Name</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Column Name</dd>
</dl>




<a id="param_2"></a>
### Please specify the Column Name or Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or id or {vIndex} or {vColumn}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please specify the Row Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or 1 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd>-1 means index of last row.<b>Optional</b><br>Default Value is Current Row</dd>
</dl>




<a id="param_4"></a>
### Please Specify the Variable Name To Assign the Value


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
Automation Class Name: GetDataTableValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
