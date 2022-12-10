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
- [Please input The Dictionary Variable](#param_0)
- [Optional - Please indicate the key for the Dictionary](#param_1)
- [Please indicate the value for the Dictionary](#param_2)
- [Optional - Please Select If Key does not Exists](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please input The Dictionary Variable


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Sample Data</dt><dd>myDictionary or {vMyDic}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please indicate the key for the Dictionary


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Sample Data</dt><dd>key1 or {vKeyName}</dd>
<dt>Remarks</dt><dd>If it is empty, it will be the value of Current Position, which can be used for Loop List command.<b>Optional</b><br>Default Value is Current Position</dd>
</dl>




<a id="param_2"></a>
### Please indicate the value for the Dictionary


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>value1 or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Select If Key does not Exists


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Error</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetDictionaryValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
