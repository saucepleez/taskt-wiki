<!--TITLE: Get DataRow Value Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
DataTable Commands &gt; Other &gt; Get DataRow Value


# Get DataRow Value Command


## What does this command do?
This command allows you to get a DataRow Value from a DataTable


## When would I want to use this command?
Use this command when you want to add a datarow to a DataTable.


## Command Parameters
- [Please indicate the DataRow Variable Name](#param_0)
- [Optional - Select value by Index or Column Name (Default is Index)](#param_1)
- [Please enter the index of the DataRow Value](#param_2)
- [Please Specify the Variable to Assign the Value](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please indicate the DataRow Variable Name


<dl>
<dt>What to input</dt><dd>Enter a existing DataRow to get Values from.</dd>
<dt>Sample Data</dt><dd>myDataRow or {vMyDataRow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Select value by Index or Column Name (Default is Index)


<dl>
<dt>What to input</dt><dd>Select whether the DataRow value should be found by index or column name</dd>
<dt>Sample Data</dt><dd>Select from Index or Column Name</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Please enter the index of the DataRow Value


<dl>
<dt>What to input</dt><dd>Enter a valid DataRow index value</dd>
<dt>Sample Data</dt><dd>0 or ColName or {vIndex}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Variable to Assign the Value


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetDataRowValueCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
