<!--TITLE: Get EMail From EMailList Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Get EMail From EMailList


# Get EMail From EMailList Command


## What does this command do?
This command allows you to get EMail from EMailList.


## When would I want to use this command?
Use this command when you want to get EMail from EMailList.


<a id="param_list"></a>
## Command Parameters
- [Please Select the EMailList Variable Name](#param_0)
- [Optional - Please Specify the EMailList Index](#param_1)
- [Please Select the EMail Variable Name](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the EMailList Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the EMailList Variable Name</dd>
<dt>Instance Type</dt><dd>MailKitEMailList</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vMailList</strong> or <strong>{vMailList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vMailList</strong> | Specify Value of Variable **vMailList** |
| <strong>{vMailList}</strong> | Specify Value of Variable **vMailList** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the EMailList Index


<dl>
<dt>What to input</dt><dd>Enter or Select the EMailList Index</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>-1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>CurrentPosition</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify the First EMail Index |
| <strong>1</strong> | Specify **1** for Index |
| <strong>-1</strong> | Specify the Last EMail Index |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the EMail Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Variable Name</dd>
<dt>Instance Type</dt><dd>MailKitEMail</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vEMailName</strong> or <strong>{vEMailName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vEMailName</strong> | Specify Variable Name **vEMailName** |
| <strong>{vEMailName}</strong> | Specify Variable Name **vEMailName** |


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
Automation Class Name: MailKitGetEMailFromEMailListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
