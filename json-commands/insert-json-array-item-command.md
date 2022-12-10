<!--TITLE: Insert JSON Array Item Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
JSON Commands &gt; Action &gt; Insert JSON Array Item


# Insert JSON Array Item Command


## What does this command do?
This command allows you to insert item to JSON Array.


## When would I want to use this command?



## Command Parameters
- [Please Specify the JSON Variable Name](#param_0)
- [Please Specify a JSON extractor (JSONPath)](#param_1)
- [Optional - Please Specify Insert Index](#param_2)
- [Please Specify Value to Insert](#param_3)
- [Optional - Please Specify Value Type to Insert](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Specify the JSON Variable Name


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>{vSomeVariable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Specify a JSON extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Input a JSON token extractor</dd>
<dt>Sample Data</dt><dd>$.id</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please Specify Insert Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or 1 or {vIndex}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Last Item</dd>
</dl>




<a id="param_3"></a>
### Please Specify Value to Insert


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Hello or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Optional - Please Specify Value Type to Insert


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Text or Number or bool or Object or Array</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Auto</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: InsertJSONArrayItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
