<!--TITLE: Get List Item Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
List Commands &gt; List Item &gt; Get List Item


# Get List Item Command


## What does this command do?
This command allows you to get an item from a List


## When would I want to use this command?
Use this command when you want to get an item from a List.


## Command Parameters
- [Please indicate the List Variable Name.](#param_0)
- [Optional - Please enter the index of the List item.](#param_1)
- [Please specify a Variable Name to Store Result](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the List Variable Name.


<dl>
<dt>What to input</dt><dd>Enter a existing List.</dd>
<dt>Sample Data</dt><dd>myList or {myList} or [1,2,3]</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please enter the index of the List item.


<dl>
<dt>What to input</dt><dd>Enter a valid List index value</dd>
<dt>Sample Data</dt><dd>0 or -1 or {vIndex}</dd>
<dt>Remarks</dt><dd>-1 means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.<b>Optional</b><br>Default Value is Current Position</dd>
</dl>




<a id="param_2"></a>
### Please specify a Variable Name to Store Result


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
Automation Class Name: GetListItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
