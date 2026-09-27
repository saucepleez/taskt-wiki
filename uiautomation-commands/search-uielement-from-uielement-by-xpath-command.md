<!--TITLE: Search UIElement From UIElement By XPath Command -->
<!-- SUBTITLE: a command in the UIAutomation group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation &gt; Search UIElement By XPath &gt; Search UIElement From UIElement By XPath


# Search UIElement From UIElement By XPath Command


## What does this command do?
This command allows you to get UIElement from UIElement using by XPath.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the UIElement Variable Name](#param_0)
- [Please Specify the Search XPath](#param_1)
- [Please Select the UIElement Variable Name](#param_2)
- [Optional - Please Specify the Wait Time for the UIElement to Exist (sec)](#param_3)
- [Optional - Please Specify the Maxinum number of Sibling Nodes for Search UIElements](#param_4)
- [Optional - Please Specify the Maxinum Depth for Search UIElements](#param_5)
- [Optional - Please Select the Variable Name to Store Window Name Result](#param_6)
- [Optional - Please Select the Variable Name to Store Window Handle Result](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Select the UIElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the UIElement Variable Name</dd>
<dt>Value</dt><dd>UIElement Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vElement or {vElement}</dd>
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
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>//Button[@Name=&quot;OK&quot;] or /Pane[1]/Button[2] or {vXPath}</dd>
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
### Please Select the UIElement Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the UIElement Variable Name</dd>
<dt>Value</dt><dd>UIElement Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vNewElement or {vNewElement}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vNewElement</strong> | Specify Value of Variable **vNewElement** |
| <strong>{vNewElement}</strong> | Specify Value of Variable **vNewElement** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Wait Time for the UIElement to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the UIElement is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Maxinum number of Sibling Nodes for Search UIElements


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vMax} or 0</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>64</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Max Siblings |
| <strong>{vMax}</strong> | Specify Value of Variable **vMax** for Max Siblings |
| <strong>0</strong> | Search All Sibling |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Maxinum Depth for Search UIElements


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vMax} or 0</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>32</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Max Depth |
| <strong>{vMax}</strong> | Specify Value of Variable **vMax** for Max Depth |
| <strong>0</strong> | Search to All Depth |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Variable Name to Store Window Name Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vWin or {vWin}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vWin</strong> | Specify Variable Name **vWin** |
| <strong>{vWin}</strong> | Specify Variable Name **vWin** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Variable Name to Store Window Handle Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>WindowHandle Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: UIAutomationSearchUIElementFromUIElementByXPathCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
