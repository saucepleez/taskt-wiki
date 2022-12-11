<!--TITLE: Add JSON Array Item Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


JSON Commands &gt; Action &gt; Add JSON Array Item


# Add JSON Array Item Command


## What does this command do?
This command allows you to add item to JSON Array.


## When would I want to use this command?



## Command Parameters
- [Please Specify the JSON Variable Name](#param_0)
- [Please Specify a JSON extractor (JSONPath)](#param_1)
- [Please Specify Value to Add](#param_2)
- [Optional - Please Specify Value Type to Add](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Specify the JSON Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>JSON</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vSomeVariable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Specify a JSON extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Input a JSON token extractor</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>$.id</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify Value to Add


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>Hello</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Specify Value Type to Add


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Text</strong> or <strong>Number</strong> or <strong>bool</strong> or <strong>Object</strong> or <strong>Array</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: AddJSONArrayItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
