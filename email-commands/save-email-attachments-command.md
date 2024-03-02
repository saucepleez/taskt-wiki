<!--TITLE: Save EMail Attachments Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Save EMail Attachments


# Save EMail Attachments Command


## What does this command do?
This command allows you to save EMail Attachments.


## When would I want to use this command?
Use this command when you want to save EMail Attachments.


<a id="param_list"></a>
## Command Parameters
- [Please Select the EMail Variable Name](#param_0)
- [Please Specify the Folder Path to Save Attachments](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the EMail Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Variable Name</dd>
<dt>Instance Type</dt><dd>MailKitEMail</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vEMailName or {vEMailName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vEMailName</strong> | Specify Variable Name **vEMailName** |
| <strong>{vEMailName}</strong> | Specify Variable Name **vEMailName** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Folder Path to Save Attachments


<dl>
<dt>What to input</dt><dd>Enter or Select the Folder Path</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>C:\Temp or {vPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\Temp</strong> | Specify **C:\Temp** for Folder Path |
| <strong>{vPath}</strong> | Specify Value of Variable **vPath** for Folder Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: MailKitSaveEMailAttachmentsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
