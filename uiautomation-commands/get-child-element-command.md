<!--TITLE: Get Child Element Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Search &gt; Get Child Element


# Get Child Element Command


## What does this command do?
This command allows you to get Child Element from AutomationElement.


## When would I want to use this command?



## Command Parameters
- [Please specify AutomationElement Variable](#param_0)
- [Optional - Set Search Parameters](#param_1)
- [Please specify a Child Element Index](#param_2)
- [Please specify a Variable to store Result AutomationElement](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please specify AutomationElement Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>AutomationElement</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Set Search Parameters


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_2"></a>
### Please specify a Child Element Index


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify a Variable to store Result AutomationElement


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vElement</strong> or <strong>{vElement}</strong></dd>
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
Automation Class Name: UIAutomationGetChildElementCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
