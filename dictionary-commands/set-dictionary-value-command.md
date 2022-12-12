<!--TITLE: Set Dictionary Value Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Item &gt; Set Dictionary Value


# Set Dictionary Value Command


## What does this command do?
This command allows you to set value in Dictionary


## When would I want to use this command?
Use this command when you want to set value in Dictionary.


## Command Parameters
- [Please Select the Please input The Dictionary Variable](#param_0)
- [Optional - Please indicate the key for the Dictionary](#param_1)
- [Please indicate the value for the Dictionary](#param_2)
- [Optional - Please Select the Please Select If Key does not Exists](#param_3)
- [Please Specify the Comment Field (Optional)](#param_4)


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
### Optional - Please indicate the key for the Dictionary


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Sample Usage</dt><dd><strong>key1</strong> or <strong>{vKeyName}</strong></dd>
<dt>Remarks</dt><dd>If it is empty, it will be the value of Current Position, which can be used for Loop List command.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Position</strong></dd>
</dl>




<a id="param_2"></a>
### Please indicate the value for the Dictionary


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>value1</strong> or <strong>{vValue}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Select the Please Select If Key does not Exists


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Error</strong> or  <strong>Ignore</strong> or  <strong>Add</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




<a id="param_4"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetDictionaryValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
