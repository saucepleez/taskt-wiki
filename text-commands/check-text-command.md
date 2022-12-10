<!--TITLE: Check Text Command -->
<!-- SUBTITLE: a command in the Text Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Text Commands &gt; Check/Get &gt; Check Text


# Check Text Command


## What does this command do?
This command allows you to check a Text


## When would I want to use this command?
Use this command when you want to check a Text


## Command Parameters
- [Please Supply the Text or Variable to Checked](#param_0)
- [Please Select the Check Method](#param_1)
- [Please Specify Text to Check or Search](#param_2)
- [Optional - Please Select Case sensitive](#param_3)
- [Please select the variable to receive the result](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Supply the Text or Variable to Checked


<dl>
<dt>What to input</dt><dd>Select or provide a variable or text value</dd>
<dt>Sample Data</dt><dd>Hello or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select the Check Method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Index of or Last Index of</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify Text to Check or Search


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ha or {vSearchedText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Select Case sensitive


<dl>
<dt>What to input</dt><dd>Indicate if only so many characters should be kept</dd>
<dt>Sample Data</dt><dd>Yes or No</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Yes</dd>
</dl>




<a id="param_4"></a>
### Please select the variable to receive the result


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>


### Addtional Info about &quot;Please select the variable to receive the result&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Contains|Result is TRUE or FALSE|||
|Start with|Result is TRUE or FALSE|||
|End with|Result is TRUE or FALSE|||
|Index of|Result is a found position. If not found, the result is -1.|||
|Last Index of|Result is the last position found. If not found, the result is -1.|||


<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CheckTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
