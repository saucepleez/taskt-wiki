<!--TITLE: Start Application Command -->
<!-- SUBTITLE: a command in the Application/Script Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Application/Script Commands &gt; Application &gt; Start Application


# Start Application Command


## What does this command do?
This command allows you to start a program or a process.


## When would I want to use this command?
Use this command to start applications by entering their name such as 'chrome.exe' or a fully qualified path to a file 'c:/some.exe'


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Path to the Application or Application Name](#param_0)
- [Optional - Please Specify the Arguments](#param_1)
- [Optional - Please Select the Wait for the Application to Complete](#param_2)
- [Optional - Please Select the Variable Name to Store Application Process Name](#param_3)
- [Optional - Please Select the Variable Name to Store Window Name](#param_4)
- [Optional - Please Select the Variable Name to Store Window Handle Result](#param_5)
- [Optional - Please Specify the Wait Time until Application Starts (ms)](#param_6)
- [Optional - Please Specify the Wait Time before Executing Next Command (ms)](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Specify the Path to the Application or Application Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Path</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>notepad or C:\Apps\myapp.exe or {vPath}</dd>
<dt>Remarks</dt><dd>Provide a valid program name or enter a full path to the script/executable including the extension.
If file does not contain folder path, this command do not supplement folder path.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>notepad</strong> | Run Notepad |
| <strong>C:\Apps\myapp.exe</strong> | Specify **C:\Apps\myapp.exe** for Path |
| <strong>{vPath}</strong> | Specify Value of Variable **vPath** for Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Arguments


<dl>
<dt>What to input</dt><dd>Enter or Select the Arguments</dd>
<dt>Sample Usage</dt><dd>-a or -verswion or {vArgs}</dd>
<dt>Remarks</dt><dd>You will need to consult documentation to determine if your executable supports arguments or flags on startup.<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>-a</strong> | Specify **-a** for Arguments |
| <strong>-verswion</strong> | Specify **-verswion** for Arguments |
| <strong>{vArgs}</strong> | Specify Value of Variable **vArgs** for Arguments |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Wait for the Application to Complete


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Variable Name to Store Application Process Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
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
### Optional - Please Select the Variable Name to Store Window Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the Variable Name to Store Window Handle Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>WindowHandle Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Wait Time until Application Starts (ms)


<dl>
<dt>What to input</dt><dd>Enter or Select the Numerical Value</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or {vValue}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>2000</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify **1** for Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Wait Time before Executing Next Command (ms)


<dl>
<dt>What to input</dt><dd>Enter or Select the Numerical Value</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or {vValue}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>2000</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify **1** for Value |
| <strong>{vValue}</strong> | Specify Value of Variable **vValue** for Value |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: StartApplicationCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
