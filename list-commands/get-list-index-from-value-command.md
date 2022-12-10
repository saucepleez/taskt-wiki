<!--TITLE: Get List Index From Value Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
List Commands &gt; Other &gt; Get List Index From Value


# Get List Index From Value Command


## What does this command do?
This command allows you want to get list index from value


## When would I want to use this command?
Use this command when you want to get list index from value


## Command Parameters
- [Please indicate the List Variable Name.](#param_0)
- [Please enter the value to search.](#param_1)
- [Optional - Please specify search method](#param_2)
- [Please specify the variable to apply index](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please indicate the List Variable Name.


<dl>
<dt>What to input</dt><dd>Enter a existing List.</dd>
<dt>Sample Data</dt><dd>myList or {myList} or [1,2,3]</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please enter the value to search.


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>0 or {vValue}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify search method


<dl>
<dt>What to input</dt><dd>First Index or Last Index</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is First Index</dd>
</dl>




<a id="param_3"></a>
### Please specify the variable to apply index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>If list does not contains value, result is -1.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetListIndexFromValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
