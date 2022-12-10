<!--TITLE: Send Email Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
EMail Commands &gt; Send Email


# Send Email Command


## What does this command do?
This command allows you to send EMail using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an EMail and have access to SMTP server credentials to generate an EMail.


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
- [Comment Field (Optional)](#param_12)


<a id="param_0"></a>
### Please specify SMTP Host Name


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Sample Data</dt><dd>smtp.mymail.com or {vHost}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify SMTP Port


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>25 or 587 or {vPort}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify SMTP Username


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>username or {vUserName}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is From Email</dd>
</dl>




<a id="param_3"></a>
### Please specify SMTP Password


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>password or {vPassword}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please specify From Email Address


<dl>
<dt>What to input</dt><dd>Specify how the 'From' field should appear.</dd>
<dt>Sample Data</dt><dd>my-robot@company.com or {vFromMail}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please specify To Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Data</dt><dd>john@company.com or {vToMail}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Optional - Please specify CC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Data</dt><dd>tom@company.com or {vCCMail}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_7"></a>
### Optional - Please specify BCC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Data</dt><dd>bob@company.com or {vBCCMail}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_8"></a>
### Optional - Please specify Email Subject


<dl>
<dt>What to input</dt><dd>Define the text subject (or variable) that the email should have.</dd>
<dt>Sample Data</dt><dd>Alert! or {vTitle}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_9"></a>
### Optional - Please specify Email Message


<dl>
<dt>What to input</dt><dd>Specify the message that should be sent.</dd>
<dt>Sample Data</dt><dd>Everything ran ok at {DateTime.Now}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_10"></a>
### Optional - Please specify Email Attachment File Path


<dl>
<dt>What to input</dt><dd>Indicates the file path to attachment.</dd>
<dt>Sample Data</dt><dd>c:\temp\file.txt or {vPath}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_11"></a>
### Optional - Please specify Secure Option


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Auto</dd>
</dl>




<a id="param_12"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MailKitSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
