<!--TITLE: Execute Tesseract OCR Command -->
<!-- SUBTITLE: a command in the Image group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Image &gt; Execute Tesseract OCR


# Execute Tesseract OCR Command


## What does this command do?
This command allows you to covert an image file into text for parsing.


## When would I want to use this command?
Use this command when you want to convert an image into text.  You can then use additional commands to parse the data.


<a id="param_list"></a>
## Command Parameters
- [Optional - Please Specify the Image File Path](#param_0)
- [Optional - Please Specify the Image variable](#param_1)
- [Please Select the Result Text](#param_2)
- [Optional - Please Specify the Tesseract Data Path, it must point to the locally installed Tesseract, tessdata folder](#param_3)
- [Optional - Please Specify the Wait Time for the File to Exist (sec)](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Optional - Please Specify the Image File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance Required</li><li>Support Extensions: png,bmp,gif,jpg,jpeg</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd>C:\temp\myimages.png or {vFilePath}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\myimages.png</strong> | File Path |
| <strong>{vFilePath}</strong> | File Path |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Image variable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Result Text


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Tesseract Data Path, it must point to the locally installed Tesseract, tessdata folder


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>C:\Program Fles\Tesseract-OCR\tessdata or {vFolderPath}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>C:\Program Files\Tesseract-OCR\tessdata</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\Program Fles\Tesseract-OCR\tessdata</strong> | Tessdata Folder Path |
| <strong>{vFolderPath}</strong> | Tessdata Folder Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Wait Time for the File to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the File is not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


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
Automation Class Name: ExecuteTesseractOCRCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
