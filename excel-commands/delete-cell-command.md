<!--TITLE: Delete Cell Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Cell &gt; Delete Cell


# Delete Cell Command


## What does this command do?
This command allows you to delete a specified cell in Excel


## When would I want to use this command?
Use this command when you want to delete a specific cell from the current sheet.


<a id="param_list"></a>
## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Indicate the range to delete ex. A1 or A1:C1](#param_1)
- [Please Select the Should the cells below shift upward after deletion?](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Indicate the range to delete ex. A1 or A1:C1


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Should the cells below shift upward after deletion?


<dl>
<dt>What to input</dt><dd>Indicate whether the row below will be shifted up to replace the old row.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelDeleteCellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 02/17/24 07:27 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
