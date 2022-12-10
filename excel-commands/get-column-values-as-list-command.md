<!--TITLE: Get Column Values As List Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Column &gt; Get Column Values As List


# Get Column Values As List Command


## What does this command do?
This command get Column values as List.


## When would I want to use this command?
Use this command when you want to get Column values as List.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Optional - Please Specify Column Type](#param_1)
- [Please Enter the Column Location or Index](#param_2)
- [Optional - Please Enter the Start Row Index](#param_3)
- [Optional - Please Enter the End Row Index](#param_4)
- [Please specify the List Variable Name to store results](#param_5)
- [Optional - Please specify the Value type to get](#param_6)
- [Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Specify Column Type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Range or RC</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Range</dd>
</dl>




<a id="param_2"></a>
### Please Enter the Column Location or Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>A or 1 or {vColumn}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Enter the Start Row Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>1 or 2 or {vRow}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is 1</dd>
</dl>




<a id="param_4"></a>
### Optional - Please Enter the End Row Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>1 or 2 or {vRow}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Last Row</dd>
</dl>




<a id="param_5"></a>
### Please specify the List Variable Name to store results


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Optional - Please specify the Value type to get


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Cell or Formula or Format or Color or Comment</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Cell</dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelGetColumnValuesAsListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
