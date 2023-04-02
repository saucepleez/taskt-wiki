<!--TITLE: Send Email Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Send Email


# Send Email Command


## What does this command do?
This command allows you to send EMail using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an EMail and have access to SMTP server credentials to generate an EMail.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the SMTP Host Name](#param_0)
- [Please Specify the SMTP Port](#param_1)
- [Please Specify the SMTP User Name](#param_2)
- [Please Specify the SMTP Password](#param_3)
- [Please Specify the From EMail Address](#param_4)
- [Please Specify the To EMail Address](#param_5)
- [Please Specify the CC EMail Address](#param_6)
- [Please Specify the BCC EMail Address](#param_7)
- [Optional - Please Specify the Email Subject](#param_8)
- [Optional - Please Specify the Email Message](#param_9)
- [Optional - Please Specify the Email Attachment File Path](#param_10)
- [Optional - Please Select the Secure Option](#param_11)
- [Optional - Please Specify the Comment Field](#param_12)


<a id="param_0"></a>
### Please Specify the SMTP Host Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Host Name</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>mail.example.com</strong> or <strong>{vHost}</strong> or <strong>smtp.example.com</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>mail.example.com</strong> | Specify **mail.example.com** for Host Name |
| <strong>{vHost}</strong> | Specify Value of Variable **vHost** for Host Name |
| <strong>smtp.example.com</strong> | Specify **smtp.example.com** for Host |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the SMTP Port


<dl>
<dt>What to input</dt><dd>Enter or Select the Port Number</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 65535</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>25</strong> or <strong>587</strong> or <strong>{vPort}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>25</strong> | Specify **25** for Port |
| <strong>587</strong> | Specify **587** for Port |
| <strong>{vPort}</strong> | Specify Value of Variable **vPort** for Port |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the SMTP User Name


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
### Please Specify the SMTP Password


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
### Please Specify the From EMail Address


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Address</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>my-robot@example.com</strong> or <strong>{vAddress}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>my-robot@example.com</strong> | Specify **my-robot@example.com** for EMail Address |
| <strong>{vAddress}</strong> | Specify Value of Variable **vAddress** for EMail Address |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the To EMail Address


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Address</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>my-robot@example.com</strong> or <strong>{vAddress}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>my-robot@example.com</strong> | Specify **my-robot@example.com** for EMail Address |
| <strong>{vAddress}</strong> | Specify Value of Variable **vAddress** for EMail Address |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Specify the CC EMail Address


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Address</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>my-robot@example.com</strong> or <strong>{vAddress}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>my-robot@example.com</strong> | Specify **my-robot@example.com** for EMail Address |
| <strong>{vAddress}</strong> | Specify Value of Variable **vAddress** for EMail Address |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Please Specify the BCC EMail Address


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Address</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>my-robot@example.com</strong> or <strong>{vAddress}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>my-robot@example.com</strong> | Specify **my-robot@example.com** for EMail Address |
| <strong>{vAddress}</strong> | Specify Value of Variable **vAddress** for EMail Address |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Email Subject


<dl>
<dt>What to input</dt><dd>Enter or Select the EMail Subject</dd>
<dt>Sample Usage</dt><dd><strong>Alert!</strong> or <strong>{vSubject}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Alert!</strong> | Specify **Alert!** for Subject |
| <strong>{vSubject}</strong> | Specify Value of Variable **vSubject** for Subject |


<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please Specify the Email Message


<dl>
<dt>What to input</dt><dd>Enter or Select the Message</dd>
<dt>Sample Usage</dt><dd><strong>Everything ran ok at {DateTime.Now}</strong> or <strong>{vMessage}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Everything ran ok at {DateTime.Now}</strong> | Send result message and current Date and Time |
| <strong>{vMessage}</strong> | Specify Value of Variable **vMessage** for Message |


<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / [next](#param_10)


</div>


<a id="param_10"></a>
### Optional - Please Specify the Email Attachment File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the File Path</dd>
<dt>Sample Usage</dt><dd><strong>C:	emp\myfile.txt</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:	emp\myfile.txt</strong> | Specify **C:	emp\myfile.txt** for File Path |
| <strong>{vPath}</strong> | Specify Value of Variable **vPath** for File Path |


<div style="font-size: 90%; text-align: center">


[prev](#param_10) / [list](#param_list) / [next](#param_11)


</div>


<a id="param_11"></a>
### Optional - Please Select the Secure Option


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Auto</strong> or  <strong>No SSL or TLS</strong> or  <strong>Use SSL or TLS</strong> or  <strong>STARTTLS</strong> or  <strong>STARTTLS When Available</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_11) / [list](#param_list) / [next](#param_12)


</div>


<a id="param_12"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_12) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: MailKitSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
