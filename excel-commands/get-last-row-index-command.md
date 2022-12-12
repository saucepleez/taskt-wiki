<!--TITLE: Get Last Row Index Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Row &gt; Get Last Row Index


# Get Last Row Index Command


## What does this command do?
This command allows you to find the last row in a used range in an Excel Workbook.


## When would I want to use this command?
Use this command to determine how many rows have been used in the Excel Workbook.  You can use this value in a **Number Of Times** Loop to get data.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Optional - Please Specify the Please Enter Letter of the Column to check](#param_1)
- [Please select the variable to receive the row number](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Specify the Please Enter Letter of the Column to check


<dl>
<dt>What to input</dt><dd>Enter a valid column letter</dd>
<dt>Sample Usage</dt><dd><strong>A</strong> or <strong>B</strong> or <strong>{vColumn}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>A</strong></dd>
</dl>




<a id="param_2"></a>
### Please select the variable to receive the row number


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelGetLastRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
