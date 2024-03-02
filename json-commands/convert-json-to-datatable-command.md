<!--TITLE: Convert JSON To DataTable Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Convert &gt; Convert JSON To DataTable


# Convert JSON To DataTable Command


## What does this command do?
This command allows you to convert JSON to DataTable.


## When would I want to use this command?
Use this command when you want to convert JSON to DataTable


<a id="param_list"></a>
## Command Parameters
- [Please Select the JSON Variable Name or JSON Value](#param_0)
- [Please Select the DataTable Variable Name](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the JSON Variable Name or JSON Value


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON Value or JSON Variable Name</dd>
<dt>Instance Type</dt><dd>JSON</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>{ &quot;id&quot;: 3, &quot;value&quot;: &quot;Hello&quot; } or [ 1, 2, &quot;Hello&quot; ] or {vJSON}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>{ &quot;id&quot;: 3, &quot;value&quot;: &quot;Hello&quot; }</strong> | Specify the JSON Object Text |
| <strong>[ 1, 2, &quot;Hello&quot; ]</strong> | Specify the JSON Array Text |
| <strong>{vJSON}</strong> | Specify Value of Variable **vJSON** for JSON |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vDataTable or {vDataTable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDataTable</strong> | Specify Variable Name **vDataTable** |
| <strong>{vDataTable}</strong> | Specify Variable Name **vDataTable** |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ConvertJSONToDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
