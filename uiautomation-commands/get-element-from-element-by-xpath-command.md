<!--TITLE: Get Element From Element By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Search &gt; Get Element From Element By XPath


# Get Element From Element By XPath Command


## What does this command do?
This command allows you to get AutomationElement from AutomationElement using by XPath.


## When would I want to use this command?



## Command Parameters
- [Please specify AutomationElement Variable](#param_0)
- [Please specify search XPath](#param_1)
- [Please specify a Variable to store Result AutomationElement](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify AutomationElement Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>AutomationElement</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify search XPath


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>//Button[@Name=&quot;OK&quot;]</strong> or <strong>{vXPath}</strong></dd>
<dt>Remarks</dt><dd>XPath does not support to use parent, following-sibling, and preceding-sibling for root element.</dd>
</dl>




<a id="param_2"></a>
### Please specify a Variable to store Result AutomationElement


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vElement</strong> or <strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: UIAutomationGetElementFromElementByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
