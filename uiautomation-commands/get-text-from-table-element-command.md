<!--TITLE: Get Text From Table Element Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Get &gt; Get Text From Table Element


# Get Text From Table Element Command


## What does this command do?
This command allows you to get Text Value from Table AutomationElement.


## When would I want to use this command?



## Command Parameters
- [Please specify AutomationElement Variable](#param_0)
- [Please specify Row Value](#param_1)
- [Please specify Column Value](#param_2)
- [Please specify a Variable to store Text Value](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please specify AutomationElement Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>AutomationElement</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>Supported Element is DataGridView, ListBox, etc.</dd>
</dl>




<a id="param_1"></a>
### Please specify Row Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> <strong>{vRow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please specify Column Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vColumn}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify a Variable to store Text Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vText</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: UIAutomationGetTextFromTableElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
