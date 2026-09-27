<!--TITLE: Get JSON Value From JSON Object Command -->
<!-- SUBTITLE: a command in the JSON group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON &gt; Get/Set &gt; Get JSON Value From JSON Object


# Get JSON Value From JSON Object Command


## What does this command do?
This command allows you to Get JSON Value From JSON Object


## When would I want to use this command?
Use this command when you want to Get JSON Value From JSON Object


<a id="param_list"></a>
## Command Parameters
- [Please Select the JSON Variable Name or JSON Value](#param_0)
- [Optional - Please Specify the JSON Extractor (JSONPath)](#param_1)
- [Please Specify the Property Name](#param_2)
- [Please Select the Variable Name to Store Result](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Select the JSON Variable Name or JSON Value


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON Value or JSON Variable Name</dd>
<dt>Value</dt><dd>JSON Variable</dd>
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
### Optional - Please Specify the JSON Extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Enter or Select the JSONPath</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>$.id or $..id or {vPath}</dd>
<dt>Remarks</dt><dd>See this URL for details. https://github.com/json-path/JsonPath<br><br>
<strong>Optional</strong><br>Default Value is <strong>$</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>$.id</strong> | Specify **id** for Root child node |
| <strong>$..id</strong> | Specify Anywhere **id** |
| <strong>{vPath}</strong> | Specify Value of Variable **vPath** for JSON Extractor |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Property Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Property Name Text</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>Name or {vName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Name</strong> | Specify **Name** for Property Name |
| <strong>{vName}</strong> | Specify Value of Variable **vName** for Property Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetJSONValueFromJSONObjectCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
