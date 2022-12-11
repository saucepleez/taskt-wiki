<!--TITLE: Filter DataTable Column By Row Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; DataTable Action &gt; Filter DataTable Column By Row Value


# Filter DataTable Column By Row Value Command


## What does this command do?
This command allows you to Filter Columns by reference to Row values.


## When would I want to use this command?
Use this command when you want to Filter Columns by reference to Row values.


## Command Parameters
- [Please select a DataTable Variable Name to Filter](#param_0)
- [Please enter the Index of the Row](#param_1)
- [Please select filter target value type](#param_2)
- [Please select filter action](#param_3)
- [Additional Parameters](#param_4)
- [Please select a DataTable Variable Name of the Filtered DataTable](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please select a DataTable Variable Name to Filter


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vTable</strong> or <strong>{vTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please enter the Index of the Row


<dl>
<dt>What to input</dt><dd>Enter a valid Column index value</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>id</strong> or <strong>0</strong> or <strong>{vRow}</strong> or <strong>-1</strong></dd>
<dt>Remarks</dt><dd>If <strong>-1</strong> is specified for Row Index, it means the last row.</dd>
</dl>




<a id="param_2"></a>
### Please select filter target value type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Text</strong> or <strong>Number</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please select filter action


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Additional Parameters


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please select a DataTable Variable Name of the Filtered DataTable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vNewTable</strong> or <strong>{vNewTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: FilterDataTableColumnByRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
