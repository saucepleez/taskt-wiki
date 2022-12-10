<!--TITLE: Set Row Values From List Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Excel Commands &gt; Row &gt; Set Row Values From List


# Set Row Values From List Command


## What does this command do?
This command set Row values from List.


## When would I want to use this command?
Use this command when you want to set a Row values from List.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the Row Index](#param_1)
- [Optional - Please Specify Column Type](#param_2)
- [Optional - Please Enter the Start Column Location](#param_3)
- [Optional - Please Enter the End Column Location](#param_4)
- [Please specify the List Variable Name to set](#param_5)
- [Optional - Please specify the Value type to set](#param_6)
- [Optional - Please specify If List Items not enough](#param_7)
- [Comment Field (Optional)](#param_8)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Excel command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Excel command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the Row Index


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>1 or 2 or {vRow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please Specify Column Type


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Range or RC</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Range</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Enter the Start Column Location


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>A or 1 or {vColumn}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is A or 1</dd>
</dl>




<a id="param_4"></a>
### Optional - Please Enter the End Column Location


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>A or 1 or {vColumn}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is End of List</dd>
</dl>




<a id="param_5"></a>
### Please specify the List Variable Name to set


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Optional - Please specify the Value type to set


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Cell or Formula or Format or Color or Comment</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Cell</dd>
</dl>




<a id="param_7"></a>
### Optional - Please specify If List Items not enough


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Ignore or Error</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Ignore</dd>
</dl>




<a id="param_8"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExcelSetRowValuesFromListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
