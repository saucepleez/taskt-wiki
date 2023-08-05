<!--TITLE: Wait For UIElement To Exists By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; Search UIElement &gt; Wait For UIElement To Exists By XPath


# Wait For UIElement To Exists By XPath Command


## What does this command do?
This command allows you to Wait until the UIElement exists using by XPath.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the UIElement Variable Name](#param_0)
- [Please Specify the Search XPath](#param_1)
- [Optional - Please Specify the Wait Time for the UIElement to Exist (sec)](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the UIElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the UIElement Variable Name</dd>
<dt>Instance Type</dt><dd>UIElement</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vElement</strong> or <strong>{vElement}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vElement</strong> | Specify Value of Variable **vElement** |
| <strong>{vElement}</strong> | Specify Value of Variable **vElement** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Search XPath


<dl>
<dt>What to input</dt><dd>Enter or Select the Search XPath</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>XPath does not support to use parent, following-sibling, and preceding-sibling for root element.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>//Button[@Name=&quot;OK&quot;]</strong> | Specify a Button whose **Name** Attribute is **OK** in descendant node of the criteria AutomationElement |
| <strong>/Pane[1]/Button[2]</strong> | Specify the **second** Button of the **first** Pane child node of the child node of the criteria AutomationElement |
| <strong>{vXPath}</strong> | Specify Value of Variable **vXPath** for XPath |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Wait Time for the UIElement to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Sample Usage</dt><dd><strong>10</strong> or <strong>{vTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the UIElement is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: UIAutomationWaitForUIElementToExistsByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/05/23 07:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
