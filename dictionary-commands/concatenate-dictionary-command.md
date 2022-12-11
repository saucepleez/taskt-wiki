<!--TITLE: Concatenate Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Action &gt; Concatenate Dictionary


# Concatenate Dictionary Command


## What does this command do?
This command allows you to concatenate two Dictionaries.


## When would I want to use this command?
Use this command when you want to concatenate two Dictionaries.


## Command Parameters
- [Please input The Dictionary Variable 1](#param_0)
- [Please input The Dictionary Variable 2](#param_1)
- [Optional - If Key already exists](#param_2)
- [Please indicate the result Dictionary](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please input The Dictionary Variable 1


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDictionary1</strong> or <strong>{vMyDic1}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please input The Dictionary Variable 2


<dl>
<dt>What to input</dt><dd>Enter a string of comma seperated values.</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myDictionary2</strong> or <strong>{vMyDic2}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - If Key already exists


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Ignore</strong> or <strong>Overwrite</strong> or <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<a id="param_3"></a>
### Please indicate the result Dictionary


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>newDic</strong> or <strong>{newDic}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConcatenateDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
