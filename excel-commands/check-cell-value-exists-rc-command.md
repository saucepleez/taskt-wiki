<!--TITLE: Check Cell Value Exists RC Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Cell &gt; Check Cell Value Exists RC


# Check Cell Value Exists RC Command


## What does this command do?
This command checks existance value from a specified Excel Cell.


## When would I want to use this command?
Use this command when you want to get a value from a specific cell.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the Row Location](#param_1)
- [Please Enter the Column Location](#param_2)
- [Please select the variable to receive the result](#param_3)
- [Optional - Value type](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the Row Location


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>1 or 2 or {vRow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Enter the Column Location


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Data</dt><dd>1 or 2 or {vColumn}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the result


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Optional - Value type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Cell or Formula or Format or Color or Comment</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Cell</dd>
</dl>


### Addtional Info about &quot;Optional - Value type&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Cell|Check cell has value or not|||
|Formula|Check cell has formula or not|||
|Back Color|Check back color is not white|||


<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelCheckCellValueExistsRCCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
