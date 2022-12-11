<!--TITLE: Set DataTable Row Values By DataTable Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Row Action &gt; Set DataTable Row Values By DataTable


# Set DataTable Row Values By DataTable Command


## What does this command do?
This command allows you to set a DataTable Row values to a DataTable by a DataTable


## When would I want to use this command?
Use this command when you want to set a DataTable Row values to a DataTable by a DataTable.


## Command Parameters
- [Please indicate the DataTable Variable Name to be setted a row](#param_0)
- [Optional - Please specify the Row index to setted values](#param_1)
- [Please specify the DataTable Variable Name to set to the DataTable](#param_2)
- [Optional - Please specify the Row index to set values](#param_3)
- [Optional - Please specify the if DataTable column does not exists](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name to be setted a row


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable Variable Name</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDataTable</strong> or <strong>{vMyDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify the Row index to setted values


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>-1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Row</strong></dd>
</dl>




<a id="param_2"></a>
### Please specify the DataTable Variable Name to set to the DataTable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please specify the Row index to set values


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>-1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Row</strong></dd>
</dl>




<a id="param_4"></a>
### Optional - Please specify the if DataTable column does not exists


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Ignore</strong> or <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetDataTableRowValuesByDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
