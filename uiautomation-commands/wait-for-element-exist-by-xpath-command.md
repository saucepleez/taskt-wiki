<!--TITLE: Wait For Element Exist By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
UIAutomation Commands &gt; Search &gt; Wait For Element Exist By XPath


# Wait For Element Exist By XPath Command


## What does this command do?
This command allows you to Wait until the AutomationElement exists using by XPath.


## When would I want to use this command?



## Command Parameters
- [Please specify AutomationElement Variable](#param_0)
- [Please specify search XPath](#param_1)
- [Please specify how many seconds to wait for the AutomationElement to exist](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify AutomationElement Variable


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>{vElement}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify search XPath


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>//Button[@Name="OK"] or {vXPath}</dd>
<dt>Remarks</dt><dd>XPath does not support to use parent, following-sibling, and preceding-sibling for root element.</dd>
</dl>




<a id="param_2"></a>
### Please specify how many seconds to wait for the AutomationElement to exist


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>10 or {vWait}</dd>
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
Automation Class Name: UIAutomationWaitForElementExistByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
