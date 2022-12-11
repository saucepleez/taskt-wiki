<!--TITLE: Set Cell RC Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Cell &gt; Set Cell RC


# Set Cell RC Command


## What does this command do?
This command sets the value of a cell.


## When would I want to use this command?
Use this command when you want to set a value to a specific cell.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter text to set](#param_1)
- [Please Enter the Cell Row](#param_2)
- [Please Enter the Cell Column](#param_3)
- [Optional - Value type](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter text to set


<dl>
<dt>What to input</dt><dd>Enter the text value that will be set.</dd>
<dt>Sample Data</dt><dd><strong>Hello World</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Enter the Cell Row


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell row.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>1</strong> or <strong>2</strong> or <strong>{vRow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Enter the Cell Column


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell column.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>1</strong> or <strong>2</strong> or <strong>{vColumn}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Optional - Value type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Cell</strong> or <strong>Formula</strong> or <strong>Format</strong> or <strong>Color</strong> or <strong>Comment</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Cell</strong></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelSetCellRCCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
