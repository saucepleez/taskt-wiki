<!--TITLE: Run PowerShell Script By Code Command -->
<!-- SUBTITLE: a command in the Application/Script group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Application/Script &gt; Windows Script File &gt; Run PowerShell Script By Code


# Run PowerShell Script By Code Command


## What does this command do?
This command allows you to run a PowerShell Script by code.


## When would I want to use this command?
Use this command when you want to run a PowerShell Script by code.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Script Code](#param_0)
- [Optional - Please Specify the Arguments](#param_1)
- [Optional - Please Select the Expand taskt Variables In Code](#param_2)
- [Optional - Please Select the Variable Name to Receive the Output](#param_3)
- [Optional - Please Select the Delete Script File After Execute](#param_4)
- [Optional - Please Select the Folder to Save Temporary Script File](#param_5)
- [Optional - Please Select the Variable Name to Store Temporary Script File Path](#param_6)
- [Optional - Please Specify the Comment Field](#param_7)


<a id="param_0"></a>
### Please Specify the Script Code


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>New-Item -Type File sample.txt or {vCode}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>New-Item -Type File sample.txt</strong> | Specify **New-Item -Type File sample.txt** for PowerShell Script |
| <strong>{vCode}</strong> | Specify Value of Variable **vCode** for PowerShell Script |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Arguments


<dl>
<dt>What to input</dt><dd>Enter or Select the Arguments</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>1 or Hello or 1 2 3 or {vArgs}</dd>
<dt>Remarks</dt><dd>Arguments are sent to the Script<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify **1** for Arguments |
| <strong>Hello</strong> | Specify **Hello** for Arguments |
| <strong>1 2 3</strong> | Specify **1 2 3** for Arguments |
| <strong>{vArgs}</strong> | Specify Value of Variable **vArgs** for Arguments |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Expand taskt Variables In Code


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Yes</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Variable Name to Receive the Output


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
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
### Optional - Please Select the Delete Script File After Execute


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Yes</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the Folder to Save Temporary Script File


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>taskt Temporary Folder</strong> or  <strong>User Temporary Folder</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>User Temporary Folder</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| taskt Temporary Folder | Generally **Document\taskt\Temporary** |
| User Temporary Folder | Generally **C:\Users\UserName\AppData\Local\Temp\taskt** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Variable Name to Store Temporary Script File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
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


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: RunPowerShellScriptByCodeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
