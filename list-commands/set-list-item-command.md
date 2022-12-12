<!--TITLE: Set List Item Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List Commands &gt; List Item &gt; Set List Item


# Set List Item Command


## What does this command do?
This command allows you want to set an item in a List


## When would I want to use this command?
Use this command when you want to set an item in a List.


## Command Parameters
- [Please indicate the List Variable Name.](#param_0)
- [Optional - Please enter the index of the List item.](#param_1)
- [Please Enter the Value of the Set](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the List Variable Name.


<dl>
<dt>What to input</dt><dd>Enter a existing List.</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>myList</strong> or <strong>{myList}</strong> or <strong>[1,2,3]</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please enter the index of the List item.


<dl>
<dt>What to input</dt><dd>Enter a valid List index value</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>-1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>-1</strong> means index of the last row. If it is empty, it will be the value of Current Position, which can be used for Loop List command.<br><br>
<strong>Optional</strong><br>Default Value is <strong>Current Position</strong></dd>
</dl>




<a id="param_2"></a>
### Please Enter the Value of the Set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SetListItemCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
