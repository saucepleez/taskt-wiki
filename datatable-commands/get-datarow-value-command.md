<!--TITLE: Get DataRow Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Other &gt; Get DataRow Value


# Get DataRow Value Command


## What does this command do?
This command allows you to get a DataRow Value from a DataTable


## When would I want to use this command?
Use this command when you want to add a datarow to a DataTable.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the DataRow Variable Name](#param_0)
- [Optional - Please Select value by Index or Column Name (Default is Index)](#param_1)
- [Please enter the index of the DataRow Value](#param_2)
- [Please Specify the Variable to Assign the Value](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please indicate the DataRow Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataRow to get Values from.</dd>
<dt>Sample Usage</dt><dd>myDataRow or {vMyDataRow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select value by Index or Column Name (Default is Index)


<dl>
<dt>What to input</dt><dd>Select whether the DataRow value should be found by index or column name</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Index</strong> or  <strong>Column Name</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please enter the index of the DataRow Value


<dl>
<dt>What to input</dt><dd>Enter a valid DataRow index value</dd>
<dt>Sample Usage</dt><dd>0 or ColName or {vIndex}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Variable to Assign the Value


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: GetDataRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
