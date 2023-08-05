<!--TITLE: Execute DLL Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


API Commands &gt; Execute DLL


# Execute DLL Command


## What does this command do?
This command processes an HTML source object


## When would I want to use this command?
Use this command to parse and extract data from a successful **HTTP Request Command**


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Path to the DLL file](#param_0)
- [Please Specify the Name of the Class that contains the Method to be Invoked](#param_1)
- [Please Specify the Name of the Method in the class to Invoke](#param_2)
- [Please Select the Variable Name to Store Result](#param_3)
- [Optional - Please Specify the Method Parameters](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Specify the Path to the DLL file


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance Required</li><li>Support Extensions: dll</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.dll</strong> or <strong>{vDLLFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myfile.dll</strong> | Specify **C:\temp\myfile.dll** for File Path |
| <strong>{vDLLFilePath}</strong> | Specify Value of Variable **vDLLFilePath** for File Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Name of the Class that contains the Method to be Invoked


<dl>
<dt>What to input</dt><dd>Enter or Select the Class Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>myNamespace.myClass</strong> or <strong>{vClass}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>myNamespace.myClass</strong> | Specify **myNamespace.myClass** for Class Name |
| <strong>{vClass}</strong> | Specify Value of Variable **vClass** for Class Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Name of the Method in the class to Invoke


<dl>
<dt>What to input</dt><dd>Enter or Select the Method Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>MyMethod</strong> or <strong>{vMethod}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>MyMethod</strong> | Specify **MyMethod** for Method Name |
| <strong>{vMethod}</strong> | Specify Value of Variable **vMethod** for Method Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Method Parameters


<dl>
<dt>What to input</dt><dd>Enter or Select the Parameters</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExecuteDLLCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/05/23 07:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
