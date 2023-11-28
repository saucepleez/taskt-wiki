<!--TITLE: Rename File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Rename File


# Rename File Command


## What does this command do?
This command renames a file at a specified destination


## When would I want to use this command?
Use this command to rename an existing file.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the File Path](#param_0)
- [Please Specify the New File Name](#param_1)
- [Optional - Please Select the Value](#param_2)
- [Optional - Please Specify the New File Extention](#param_3)
- [Optional - Please Select the When File Name Same After the Change](#param_4)
- [Optional - Please Specify the Wait Time for the File to Exist (sec)](#param_5)
- [Optional - Please Select the Variable Name to Store File Path Before Rename](#param_6)
- [Optional - Please Select the Variable Name to Store File Path After Rename](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Specify the File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension <string>Not</string> Required, Existance <string>Not</string> Required</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.txt</strong> or <strong>{vFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myfile.txt</strong> | Specify **C:\temp\myfile.txt** for File Path |
| <strong>{vFilePath}</strong> | Specify Value of Variable **vFilePath** for File Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the New File Name


<dl>
<dt>What to input</dt><dd>Enter or Select the New File Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>newfile</strong> or <strong>{vNewFileName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>newfile</strong> | Specify **newfile** for File Name |
| <strong>{vNewFileName}</strong> | Specify Value of Variable **vNewFileName** for File Name |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Value


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>Force Combine New Extension</strong> or  <strong>Contains New File Name</strong> or  <strong>Use Before Rename Path</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>


#### Addtional Info about &quot;Optional - Please Select the Value&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Auto|If the New File Name does not contain an Extension and Not specified New Extension, it will automatically be given the extension of the path before the Rename.|||
|Force Combine New Extension|Forces combining the specified extensions with the New Extension|||
|Contains New File Name|Determine that New File Name contains the Extension and Do NOT add the Extension to the New File Name|||
|Use Before Rename Path|Forces before Rename File Path extensions to be combined|||


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the New File Extention


<dl>
<dt>What to input</dt><dd>Enter or Select the New File Extention</dd>
<dt>Sample Usage</dt><dd><strong>txt</strong> or <strong>{vExtension}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>txt</strong> | Specify **txt** for Extension |
| <strong>{vExtension}</strong> | Specify Value of Variable **vExtension** for Extension |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the When File Name Same After the Change


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Ignore</strong> | Nothing to do |
| <strong>Error</strong> | Rise a Error |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Wait Time for the File to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>10</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the File is not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Select the Variable Name to Store File Path Before Rename


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd><strong>vPath</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vPath</strong> | Specify Variable Name **vPath** |
| <strong>{vPath}</strong> | Specify Variable Name **vPath** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Variable Name to Store File Path After Rename


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


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
Automation Class Name: RenameFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/28/23 11:23 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
