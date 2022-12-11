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
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>smtp.mymail.com</strong> or <strong>{vHost}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify SMTP Port


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the SMTP service</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>25</strong> or <strong>587</strong> or <strong>{vPort}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify SMTP Username


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the SMTP service</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>username</strong> or <strong>{vUserName}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>From Email</strong></dd>
</dl>




<a id="param_3"></a>
### Please specify SMTP Password


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the SMTP service</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>password</strong> or <strong>{vPassword}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please specify From Email Address


<dl>
<dt>What to input</dt><dd>Specify how the 'From' field should appear.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>my-robot@company.com</strong> or <strong>{vFromMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please specify To Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>john@company.com</strong> or <strong>{vToMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Optional - Please specify CC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>tom@company.com</strong> or <strong>{vCCMail}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_7"></a>
### Optional - Please specify BCC Email Address


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>bob@company.com</strong> or <strong>{vBCCMail}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_8"></a>
### Optional - Please specify Email Subject


<dl>
<dt>What to input</dt><dd>Define the text subject (or variable) that the email should have.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>Alert!</strong> or <strong>{vTitle}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_9"></a>
### Optional - Please specify Email Message


<dl>
<dt>What to input</dt><dd>Specify the message that should be sent.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>Everything ran ok at {DateTime.Now}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_10"></a>
### Optional - Please specify Email Attachment File Path


<dl>
<dt>What to input</dt><dd>Indicates the file path to attachment.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>c:\temp\file.txt</strong> or <strong>{vPath}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_11"></a>
### Optional - Please specify Secure Option


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Auto</strong> or  <strong>No SSL or TLS</strong> or  <strong>Use SSL or TLS</strong> or  <strong>STARTTLS</strong> or  <strong>STARTTLS When Available</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<a id="param_12"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MailKitSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
