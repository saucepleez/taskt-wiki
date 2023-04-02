<!--TITLE: Insert JSON Object Property Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Action &gt; Insert JSON Object Property


# Insert JSON Object Property Command


## What does this command do?
This command allows you to add property to JSON Object.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the JSON Object Variable Name](#param_0)
- [Please Specify the JSON Extractor (JSONPath)](#param_1)
- [Please Specify the Property Name](#param_2)
- [Please Specify the Value to Add](#param_3)
- [Optional - Please Select the Value Type to Add](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Select the JSON Object Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the JSON <strong>Variable Name</strong></dd>
<dt>Value</dt><dd>JSON Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command And also The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vJSON</strong> or <strong>{vJSON}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vJSON</strong> | Specify Variable Name **vJSON** |
| <strong>{vJSON}</strong> | Specify Variable Name **vJSON** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the JSON Extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Enter or Select the JSONPath</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>$.id</strong> or <strong>$..id</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd>See this URL for details. https://github.com/json-path/JsonPath</dd>
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
<dt>What to input</dt><dd>Enter or Select the Property Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Name</strong> or <strong>{vName}</strong></dd>
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
### Please Specify the Value to Add


<dl>
<dt>What to input</dt><dd>Enter or Select the Value</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>1</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Hello</strong> | Add Text **Hello** |
| <strong>1</strong> | Add Number **Hello** |
| <strong>{vValue}</strong> | Add Value of Variable **vValue** |
| <strong>{ &quot;id&quot;: 1, &quot;value&quot;: &quot;Hello&quot; }</strong> | Add JSON Object |
| <strong>[ 1, 2, &quot;Hello&quot; ]</strong> | Add JSON Array |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Value Type to Add


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>Text</strong> or  <strong>Number</strong> or  <strong>null</strong> or  <strong>bool</strong> or  <strong>Object</strong> or  <strong>Array</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Auto</strong> | Automatically determines the Value Type |
| <strong>Text</strong> | Specify **Text** for Value Type |
| <strong>Number</strong> | Specify **Number** for Value Type |
| <strong>bool</strong> | Specify **bool** for Value Type |
| <strong>Object</strong> | Specify JSON Object for Value Type |
| <strong>Array</strong> | Specify Array Object for Value Type |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: InsertJSONObjectPropertyCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
