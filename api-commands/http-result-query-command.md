<!--TITLE: HTTP Result Query Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
API Commands &gt; HTTP Result Query


# HTTP Result Query Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


## Command Parameters
- [Select variable containing HTML](#param_0)
- [XPath Query](#param_1)
- [Apply Query Result To Variable](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Select variable containing HTML


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### XPath Query


<dl>
<dt>What to input</dt><dd>Enter the XPath Query and the item will be extracted.</dd>
<dt>Sample Data</dt><dd>@//[@id="aso_search_form_anchor"]/div/input</dd>
<dt>Remarks</dt><dd>You can use Chrome Dev Tools to click an element and copy the XPath.</dd>
</dl>




<a id="param_2"></a>
### Apply Query Result To Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
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
Automation Class Name: HTTPQueryResultCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
