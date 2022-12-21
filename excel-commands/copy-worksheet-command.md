<!--TITLE: Copy Worksheet Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Sheet &gt; Copy Worksheet


# Copy Worksheet Command


## What does this command do?
This command copy a Excel Worksheet.


## When would I want to use this command?
Use this command when you want to copy a new worksheet to an Excel Instance


<a id="param_list"></a>
## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the target worksheet name](#param_1)
- [Optional - Please Enter the new worksheet name](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Enter the target worksheet name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>mySheet</strong> or <strong>Current Sheet</strong> or <strong>{vSheet}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Enter the new worksheet name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>newSheet</strong> or <strong>{vNewSheet}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelCopyWorksheetCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
