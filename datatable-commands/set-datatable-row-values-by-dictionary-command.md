<!--TITLE: Set DataTable Row Values By Dictionary Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Row Action &gt; Set DataTable Row Values By Dictionary


# Set DataTable Row Values By Dictionary Command


## What does this command do?
This command allows you to set a DataTable Row values to a DataTable by a Dictionary


## When would I want to use this command?
Use this command when you want to set a DataTable Row values to a DataTable by a Dictionary.


## Command Parameters
- [Please indicate the DataTable Variable Name to be setted a row](#param_0)
- [Optional - Please specify the Row index to set values](#param_1)
- [Please specify the Dictionary Variable Name to set to the DataTable](#param_2)
- [Optional - Please specify the if Dictionary key does not exists](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name to be setted a row


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable Variable Name</dd>
<dt>Sample Data</dt><dd>myDataTable or {vMyDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Row index to set values


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or 1 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd>-1 means index of the last row.<b>Optional</b><br>Default Value is Current Row</dd>
</dl>




<a id="param_2"></a>
### Please specify the Dictionary Variable Name to set to the DataTable


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please specify the if Dictionary key does not exists


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Error</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetDataTableRowValuesByDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
