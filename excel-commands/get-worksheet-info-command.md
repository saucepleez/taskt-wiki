<!--TITLE: Get Worksheet Info Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Sheet &gt; Get Worksheet Info


# Get Worksheet Info Command


## What does this command do?
This command allows you to get a sheet info.


## When would I want to use this command?
Use this command when you want to launch a new instance of Excel.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please select the sheet name](#param_1)
- [Please select the information type](#param_2)
- [Please select the variable to receive a sheet info](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Signifies a unique name that will represemt the application instance.  This unique name allows you to refer to the instance by name in future commands, ensuring that the commands you specify run against the correct application.</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the sheet name


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>mySheet or Current Sheet or {vSheet}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the information type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Name or Visible or Is first sheet or Is last sheet or Next sheet or Previous sheet or Sheet index</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive a sheet info


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelGetWorksheetInfoCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
