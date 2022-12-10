<!--TITLE: Get JSON Value List Command -->
<!-- SUBTITLE: a command in the JSON Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
JSON Commands &gt; Get/Set &gt; Get JSON Value List


# Get JSON Value List Command


## What does this command do?
This command allows you to parse a JSON object into a list.


## When would I want to use this command?
Use this command when you want to extract data from a JSON object


## Command Parameters
- [Supply the JSON text or variable requiring extraction](#param_0)
- [Specify a JSON extractor (JSONPath)](#param_1)
- [Please select the variable to receive the extracted Result](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Supply the JSON text or variable requiring extraction


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>{"id":2} or {vSomeVariable}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Specify a JSON extractor (JSONPath)


<dl>
<dt>What to input</dt><dd>Input a JSON token extractor</dd>
<dt>Sample Data</dt><dd>$.id</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the variable to receive the extracted Result


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetJSONValueListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
