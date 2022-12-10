<!--TITLE: Execute DLL Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
API Commands &gt; Execute DLL


# Execute DLL Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


## Command Parameters
- [Please indicate the path to the DLL file](#param_0)
- [Please select the name of the class that contains the method to be invoked](#param_1)
- [Please select the name of the method in the class to invoke](#param_2)
- [Please select the variable to receive the result](#param_3)
- [Please indicate the parameters (if required)](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please indicate the path to the DLL file


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the DLL File</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.dll or {vDLLFilePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please select the name of the class that contains the method to be invoked


<dl>
<dt>What to input</dt><dd>Provide the parent class name in the DLL.</dd>
<dt>Sample Data</dt><dd>Namespace should be included, myNamespace.myClass</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select the name of the method in the class to invoke


<dl>
<dt>What to input</dt><dd>Provide the method name in the DLL to be invoked.</dd>
<dt>Sample Data</dt><dd>GetSomething</dd>
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
### Please indicate the parameters (if required)


<dl>
<dt>What to input</dt><dd>Select the 'Generate Parameters' button once you have indicated a file, class, and method.</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExecuteDLLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
