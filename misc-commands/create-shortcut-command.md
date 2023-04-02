<!--TITLE: Create Shortcut Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Misc Commands &gt; Other &gt; Create Shortcut


# Create Shortcut Command


## What does this command do?
This command allow to create shortcut file


## When would I want to use this command?
Use this command when you want to create shortcut file


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Target File, Folder, or URL](#param_0)
- [Please Specify the Saved Shortcut Path](#param_1)
- [Optional - Please Specify the Shortcut Description](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Specify the Target File, Folder, or URL


<dl>
<dt>What to input</dt><dd>Enter or Select the File, Folder, or URL</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>**C:\temp\target.txt or **C:\temp\ or **http://example.com or **{vPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| **C:\temp\target.txt | Specify **C:\temp\target.txt for Target File |
| **C:\temp\ | Specify **C:\temp\ for Target Folder |
| **http://example.com | Specify **http://example.com for Target URL |
| **{vPath} | Specify Value of Variable **vPath for Target File, Folder, or URL |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Saved Shortcut Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Shortcut Path</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: No</li><li>File Extension and Existance: Extension Required, Existance <string>Not</string> Required</li><li>Support Extensions: lnk,url</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\shortcut.lnk</strong> or <strong>C:\temp\shortcut.url</strong> or <strong>{vShortcut}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\shortcut.lnk</strong> | Specify **C:\temp\shortcut.lnk** for Shortcut Path |
| <strong>C:\temp\shortcut.url</strong> | Specify **C:\temp\shortcut.url** for Shortcut Path |
| <strong>{vShortcut}</strong> | Specify Value of Variable **vShortcut** for Shortcut Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Shortcut Description


<dl>
<dt>What to input</dt><dd>Enter or Select the Description</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: CreateShortcutCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
