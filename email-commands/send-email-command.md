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
- [Please specify SMTP Host Name](#param_0)
- [Please specify SMTP Port](#param_1)
- [Optional - Please specify SMTP Username](#param_2)
- [Please specify SMTP Password](#param_3)
- [Please specify From Email Address](#param_4)
- [Please specify To Email Address](#param_5)
- [Optional - Please specify CC Email Address](#param_6)
- [Optional - Please specify BCC Email Address](#param_7)
- [Optional - Please specify Email Subject](#param_8)
- [Optional - Please specify Email Message](#param_9)
- [Optional - Please specify Email Attachment File Path](#param_10)
- [Optional - Please specify Secure Option](#param_11)
- [Optional - Please Specify the Comment Field](#param_12)


<a id="param_0"></a>
### Please specify SMTP Host Name


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>smtp.mymail.com</strong> or <strong>{vHost}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify SMTP Port


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the SMTP service</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>25</strong> or <strong>587</strong> or <strong>{vPort}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please specify SMTP Username


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the SMTP service</dd>
<dt>Sample Usage</dt><dd><strong>username</strong> or <strong>{vUserName}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>From Email</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please specify SMTP Password


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the SMTP service</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>password</strong> or <strong>{vPassword}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please specify From Email Address


<dl>
<dt>What to input</dt><dd>Specify how the 'From' field should appear.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>my-robot@company.com</strong> or <strong>{vFromMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please specify To Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>john@company.com</strong> or <strong>{vToMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please specify CC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Usage</dt><dd><strong>tom@company.com</strong> or <strong>{vCCMail}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please specify BCC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Usage</dt><dd><strong>bob@company.com</strong> or <strong>{vBCCMail}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please specify Email Subject


<dl>
<dt>What to input</dt><dd>Define the text subject (or variable) that the email should have.</dd>
<dt>Sample Usage</dt><dd><strong>Alert!</strong> or <strong>{vTitle}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please specify Email Message


<dl>
<dt>What to input</dt><dd>Specify the message that should be sent.</dd>
<dt>Sample Usage</dt><dd><strong>Everything ran ok at {DateTime.Now}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / [next](#param_10)


</div>


<a id="param_10"></a>
### Optional - Please specify Email Attachment File Path


<dl>
<dt>What to input</dt><dd>Indicates the file path to attachment.</dd>
<dt>Sample Usage</dt><dd><strong>c:\temp\file.txt</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_10) / [list](#param_list) / [next](#param_11)


</div>


<a id="param_11"></a>
### Optional - Please specify Secure Option


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
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
This page was generated on 01/01/23 08:43 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
