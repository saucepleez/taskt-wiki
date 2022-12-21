<!--TITLE: Insert JSON Array Item Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Action &gt; Insert JSON Array Item


# Insert JSON Array Item Command


## What does this command do?
This command allows you to insert item to JSON Array.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Specify the JSON Variable Name](#param_0)
- [Please Specify a JSON extractor (JSONPath)](#param_1)
- [Optional - Please Specify Insert Index](#param_2)
- [Please Specify Value to Insert](#param_3)
- [Optional - Please Specify Value Type to Insert](#param_4)
- [Please Specify the Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Specify the JSON Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>JSON</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>{vSomeVariable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify a JSON extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Input a JSON token extractor</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>$.id</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify Insert Index


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Last Item</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify Value to Insert


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>Hello</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify Value Type to Insert


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>Text</strong> or  <strong>Number</strong> or  <strong>null</strong> or  <strong>bool</strong> or  <strong>Object</strong> or  <strong>Array</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: InsertJSONArrayItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
