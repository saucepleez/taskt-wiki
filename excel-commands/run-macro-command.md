<!--TITLE: Run Macro Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Other &gt; Run Macro


# Run Macro Command


## What does this command do?
This command runs a macro.


## When would I want to use this command?
Use this command when you want to get a run a specific macro in the Excel workbook.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the macro name](#param_1)
- [Optional - Please Enter the macro argument1](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the macro name


<dl>
<dt>What to input</dt><dd>Enter the name of the macro as it exists in the spreadsheet</dd>
<dt>Sample Data</dt><dd>Macro1 or Module1.Macro1 or {vMacro}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please Enter the macro argument1


<dl>
<dt>What to input</dt><dd>Enter the value of the macro argument</dd>
<dt>Sample Data</dt><dd>1 or Hello or {vArgument}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelRunMacroCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
