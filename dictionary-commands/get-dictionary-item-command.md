<!--TITLE: Get Dictionary Item Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Item &gt; Get Dictionary Item


# Get Dictionary Item Command


## What does this command do?
This command allows you to get value in Dictionary


## When would I want to use this command?
Use this command when you want to get value in Dictionary.


## Command Parameters
- [Please input The Dictionary Variable](#param_0)
- [Optional - Please indicate the key for the Dictionary](#param_1)
- [Please indicate the variable to apply result](#param_2)
- [Optional - Please Select If Key does not Exists](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please input The Dictionary Variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDictionary</strong> or <strong>{vMyDic}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please indicate the key for the Dictionary


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>key1</strong> or <strong>{vKeyName}</strong></dd>
<dt>Remarks</dt><dd>If it is empty, it will be the value of Current Position, which can be used for Loop List command.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Position</strong></dd>
</dl>




<a id="param_2"></a>
### Please indicate the variable to apply result


<dl>
<dt>What to input</dt><dd>Enter a unique dataset name that will be used later to traverse over the data</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vMyData</strong> or <strong>{myData}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Select If Key does not Exists


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Error</strong> or  <strong>Set Empty</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Error</strong></dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetDictionaryValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
