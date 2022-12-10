<!--TITLE: Execute Script Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Web Browser Commands &gt; Actions &gt; Execute Script


# Execute Script Command


## What does this command do?
This command allows you to execute a script in a Selenium web browser session.


## When would I want to use this command?



## Command Parameters
- [Please Enter the instance name (ex. myInstance, {{vInstance})](#param_0)
- [Optional - Please Specify script code type (Default is Code)](#param_1)
- [Please Enter the script code](#param_2)
- [Optional - Please Enter the timeout in seconds (Default is 0)](#param_3)
- [Optional - Supply Argument](#param_4)
- [Optional - Please select the variable to receive the data](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please Enter the instance name (ex. myInstance, {{vInstance})


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Browser command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Specify script code type (Default is Code)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Code or File</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_2"></a>
### Please Enter the script code


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If selected Code plese enter script code.
If selected File, please enter script file path.</dd>
</dl>




<a id="param_3"></a>
### Optional - Please Enter the timeout in seconds (Default is 0)


<dl>
<dt>What to input</dt><dd>If less than or equal to 0, wait for the script to finish.</dd>
<dt>Sample Data</dt><dd>0 or 10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>time >= 1 is async, time <= 0 is sync<b>Optional</b><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Supply Argument


<dl>
<dt>What to input</dt><dd>The value of the argument can be obtained with 'arguments[0]' in code.</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_5"></a>
### Optional - Please select the variable to receive the data


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable or {vVariableName}</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.<b>Optional</b><br></dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserExecuteScriptCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
