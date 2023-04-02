<!--TITLE: Recieve EMailList Using IMAP Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Recieve EMailList Using IMAP


# Recieve EMailList Using IMAP Command


## What does this command do?
This command allows you to get EMailList(Emails) using IMAP protocol.


## When would I want to use this command?
Use this command when you want to get EMailList(Emails) using IMAP protocol. Result Variable Type is EMailList.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Host Name](#param_0)
- [Please Specify the Port](#param_1)
- [Please Specify the Username](#param_2)
- [Please Specify the Password](#param_3)
- [Optional - Please Select the Secure Option](#param_4)
- [Please Select the EMailList Variable Name](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Specify the Host Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Host Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>mail.example.com</strong> or <strong>{vHost}</strong> or <strong>imap.example.com</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>mail.example.com</strong> | Specify **mail.example.com** for Host Name |
| <strong>{vHost}</strong> | Specify Value of Variable **vHost** for Host Name |
| <strong>imap.example.com</strong> | Specify **imap.example.com** for Host |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Port


<dl>
<dt>What to input</dt><dd>Enter or Select the Port Number</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 65535</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>143</strong> or <strong>993</strong> or <strong>{vPort}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>143</strong> | Specify **143** for Port |
| <strong>993</strong> | Specify **993** for Port |
| <strong>{vPort}</strong> | Specify Value of Variable **vPort** for Port |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Username


<dl>
<dt>What to input</dt><dd>Enter or Select the Username</dd>
<dt>Sample Usage</dt><dd><strong>john</strong> or <strong>john@example.com</strong> or <strong>{vUser}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>john</strong> | Specify **john** for Username |
| <strong>john@example.com</strong> | Specify **john@example.com** for Username |
| <strong>{vUser}</strong> | Specify Value of Variable **vUser** for Username |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Password


<dl>
<dt>What to input</dt><dd>Password</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>password</strong> or <strong>{vPass}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>password</strong> | Specify **password** for Password |
| <strong>{vPass}</strong> | Specify Value of Variable **vPass** for Password |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Secure Option


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>No SSL or TLS</strong> or  <strong>Use SSL or TLS</strong> or  <strong>STARTTLS</strong> or  <strong>STARTTLS When Available</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Select the EMailList Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the EMailList Variable Name</dd>
<dt>Value</dt><dd>MailKitEMailList Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vEMailList</strong> or <strong>{vEMailList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vEMailList</strong> | Specify Variable Name **vEMailList** |
| <strong>{vEMailList}</strong> | Specify Variable Name **vEMailList** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: MailKitRecieveEmailListUsingIMAPCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
