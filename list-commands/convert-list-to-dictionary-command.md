<!--TITLE: Convert List To Dictionary Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
List Commands &gt; Convert &gt; Convert List To Dictionary


# Convert List To Dictionary Command


## What does this command do?
This command convert a List to Dictionary.


## When would I want to use this command?



## Command Parameters
- [Supply the List to convert](#param_0)
- [Optional - Please Select Dictionary Keys Type](#param_1)
- [Optional - Supply the Dictionary Keys Name](#param_2)
- [Optional - When the number of items in the List is greater than the number of Keys](#param_3)
- [Optional - When the number of Keys is greater than the number of items in the List](#param_4)
- [Please select the variable to receive the Dictionary Variable](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Supply the List to convert


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vList or {vList}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Select Dictionary Keys Type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Key Prefix</dd>
</dl>




<a id="param_2"></a>
### Optional - Supply the Dictionary Keys Name


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>a,b,c or {vKeys}</dd>
<dt>Remarks</dt><dd>If keys is empty, Dictionary key is item0, item1, ...<b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Optional - When the number of items in the List is greater than the number of Keys


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_4"></a>
### Optional - When the number of Keys is greater than the number of items in the List


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_5"></a>
### Please select the variable to receive the Dictionary Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertListToDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
