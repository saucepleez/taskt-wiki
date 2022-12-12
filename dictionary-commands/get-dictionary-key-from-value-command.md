<!--TITLE: Get Dictionary Key From Value Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Key &gt; Get Dictionary Key From Value


# Get Dictionary Key From Value Command


## What does this command do?
This command allows you to get Dictionary key Name from Value


## When would I want to use this command?
Use this command when you want to get Dictionary key Name from Value.


## Command Parameters
- [Please Select the Please input The Dictionary Variable](#param_0)
- [Please indicate the value for the Dictionary](#param_1)
- [Please indicate the variable to apply Key name](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Select the Please input The Dictionary Variable


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>myDictionary</strong> or <strong>{vMyDic}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the value for the Dictionary


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>value1</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>If Key not found, result is empty.</dd>
</dl>




<a id="param_2"></a>
### Please indicate the variable to apply Key name


<dl>
<dt>What to input</dt><dd>Enter a unique dataset name that will be used later to traverse over the data</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>vKey</strong> or <strong>{vKey}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetDictionaryKeyFromValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
