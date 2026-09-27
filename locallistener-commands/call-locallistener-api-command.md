<!--TITLE: Call LocalListener API Command -->
<!-- SUBTITLE: a command in the LocalListener group. -->
[Go To Automation Commands Overview](/automation-commands.md)


LocalListener &gt; Call LocalListener API


# Call LocalListener API Command


## What does this command do?
This command allows you to make API calls to taskt has LocalListener enabled


## When would I want to use this command?
Use this command when you  want to make API calls to taskt has LocalListener enabled


<a id="param_list"></a>
## Command Parameters
- [Please Specify the taskt IP Address or URL](#param_0)
- [Optional - Please Specify the Port](#param_1)
- [Please Select the Parameter Type](#param_2)
- [Optional - Please Select the Execution Preference](#param_3)
- [Optional - Please Specify the Script Parameter Data](#param_4)
- [Please Specify the Request Timeout (sec)](#param_5)
- [Please Select the Variable Name to Store Result](#param_6)
- [Optional - Please Select the Use Auth Key](#param_7)
- [Optional - Please Specify the Auth Key](#param_8)
- [Optional - Please Specify the Comment Field](#param_9)


<a id="param_0"></a>
### Please Specify the taskt IP Address or URL


<dl>
<dt>What to input</dt><dd>Enter or Select the IP Address</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>192.168.0.15 or {vRemoteHost} or {vIP}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>192.168.0.15</strong> | Specify **192.168.0.15** for IP Address |
| <strong>{vRemoteHost}</strong> | Specify Value of Variable **vRemoteHost** for IP Address |
| <strong>{vIP}</strong> | Specify **{{{vIP}}}** for IP Address |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Port


<dl>
<dt>What to input</dt><dd>Enter or Select the Port</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>19312 or {vPort}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>19312</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>19312</strong> | Specify **19312** for Port |
| <strong>{vPort}</strong> | Specify Value of Variable **vPort** for Port |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Parameter Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Run Raw Script Data</strong> or  <strong>Run Local File</strong> or  <strong>Run Remote File</strong> or  <strong>Run Command Json</strong> or  <strong>Get Engine Status</strong> or  <strong>Restart taskt</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Execution Preference


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Continue Execution</strong> or  <strong>Await For Result</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Continue Execution</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Script Parameter Data


<dl>
<dt>What to input</dt><dd>Enter or Select the Script Parameter</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the Request Timeout (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Request Timeout</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>1000 or {vTime}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1000</strong> | Specify **1000** for Timeout |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Timeout |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Use Auth Key


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Auth Key


<dl>
<dt>What to input</dt><dd>Enter or Select the Auth Key</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>01234567-89ab-cdef-0123-456789abcedf or {vKey}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>01234567-89ab-cdef-0123-456789abcedf</strong> | Specify **01234567-89ab-cdef-0123-456789abcedf** for Auth Key |
| <strong>{vKey}</strong> | Specify Value of Variable **vKey** for Auth Key |


<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: CallLocalListenerAPICommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
