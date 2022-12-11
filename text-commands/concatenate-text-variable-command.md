<!--TITLE: Concatenate Text Variable Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Text Commands &gt; Action &gt; Concatenate Text Variable


# Concatenate Text Variable Command


## What does this command do?
This command allows you to you to concatenate text to Text Variable.


## When would I want to use this command?
Use this command when you want to concatenate text to Text Variable.


## Command Parameters
- [Please specify Target Text Variable Name](#param_0)
- [Please specify Text to Concatenate](#param_1)
- [Optional - Please select Insert Line Break before Concatenate or Not](#param_2)
- [Optional - Please select Concatenate Position](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please specify Target Text Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vText</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify Text to Concatenate


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Hello</strong> or <strong>{vText}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please select Insert Line Break before Concatenate or Not


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<a id="param_3"></a>
### Optional - Please select Concatenate Position


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Before Variable Value</strong> or <strong>After Variable Value</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>After Variable Value</strong></dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConcatenateTextVariableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
