<!--TITLE: Split Range By Column Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Range &gt; Split Range By Column


# Split Range By Column Command


## What does this command do?
This command gets text from a specified Excel Range and splits it into separate ranges by column.


## When would I want to use this command?
Use this command when you want to split a range into separate ranges.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the First Cell Location (ex. A1 or B2)](#param_1)
- [Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)](#param_2)
- [Please Enter the Column Name](#param_3)
- [Please indicate the output directory](#param_4)
- [Please Select the Indicate the File Type to save as](#param_5)
- [Please Specify the Assign DataTable List to Variable](#param_6)
- [Please Specify the Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the First Cell Location (ex. A1 or B2)


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Enter the Second Cell Location (ex. A1 or B2, Leave Blank for All)


<dl>
<dt>What to input</dt><dd>Enter the actual location of the cell.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Enter the Column Name


<dl>
<dt>What to input</dt><dd>Enter the name of the column you wish to split by.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please indicate the output directory


<dl>
<dt>What to input</dt><dd>Enter or Select the new directory for the split Excel Files.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please Select the Indicate the File Type to save as


<dl>
<dt>What to input</dt><dd>Specify the file format type for the split ranges</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>xlsx</strong> or  <strong>csv</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Please Specify the Assign DataTable List to Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_7"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelSplitRangeByColumnCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
