<!--TITLE: Get HTML Text By XPath Command -->
<!-- SUBTITLE: a command in the Data Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Data Commands &gt; Get HTML Text By XPath


# Get HTML Text By XPath Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


<a id="param_list"></a>
## Command Parameters
- [Please Specify the HTML](#param_0)
- [Please Specify the XPath Query](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the HTML


<dl>
<dt>What to input</dt><dd>Enter or Select the HTML</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>**{vHTML} or <strong><html><head>...</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| **{vHTML} | Specify Value of Variable **vHTML for HTML |
| <strong><html><head>...</strong> | Specify **<html><head>...** for HTML |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the XPath Query


<dl>
<dt>What to input</dt><dd>Enter or Select the XPath Query</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>@//*[@id=&quot;aso_search_form_anchor&quot;]/div/input</dd>
<dt>Remarks</dt><dd>You can use Chrome Dev Tools to click an element and copy the XPath.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


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
Automation Class Name: HTMLGetHTMLTextByXPath
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/05/23 07:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
