<!--TITLE: Parse JSON Array Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
JSON Commands &gt; Convert &gt; Parse JSON Array


# Parse JSON Array Command


## What does this command do?
This command allows you to parse a JSON Array into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
- [Supply the JSON Array or Variable](#param_0)
- [Please select the variable to receive the List](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Supply the JSON Array or Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable or json array value</dd>
<dt>Sample Data</dt><dd>[1,2,3] or [{obj1},{obj2}] or {vArrayVariable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the variable to receive the List


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ParseJSONArrayCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
