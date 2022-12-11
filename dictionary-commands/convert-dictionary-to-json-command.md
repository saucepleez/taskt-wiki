<!--TITLE: Convert Dictionary To JSON Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Convert &gt; Convert Dictionary To JSON


# Convert Dictionary To JSON Command


## What does this command do?
This command allows you to get JSON from Dictionary


## When would I want to use this command?
Use this command when you want to get JSON from Dictionary.


## Command Parameters
- [Please input The Dictionary Variable](#param_0)
- [Please indicate the variable to apply JSON](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please input The Dictionary Variable


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDictionary</strong> or <strong>{vMyDic}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the variable to apply JSON


<dl>
<dt>What to input</dt><dd>Enter a unique dataset name that will be used later to traverse over the data</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vJSON</strong> or <strong>{vJSON}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertDictionaryToJSONCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
