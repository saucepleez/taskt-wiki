<!--TITLE: Send SMTP Email Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Misc Commands &gt; Network/Internet &gt; Send SMTP Email


# Send SMTP Email Command


## What does this command do?
This command allows you to send email using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an email and have access to SMTP server credentials to generate an email.


## Command Parameters
- [Host Name (ex. mail.example.com, {vHost})](#param_0)
- [Port (ex. 25, 587, {vPort})](#param_1)
- [Username (ex. myUserName, {vUserName})](#param_2)
- [Password (ex. myPassword, {vPassword})](#param_3)
- [From Email (ex. myaccount@example.com, {vMail})](#param_4)
- [To Email (ex. toaccount@exmaple.com, {vMail})](#param_5)
- [Subject (ex. Alert Mail, {vTitle})](#param_6)
- [Body (ex. Everything ok, {vMailMessage})](#param_7)
- [Optional - Attachment Path (ex. C:\temp\file.txt, {vPath})](#param_8)
- [Indicate if SSL should be used](#param_9)
- [SSL Validation](#param_10)
- [Comment Field (Optional)](#param_11)


<a id="param_0"></a>
### Host Name (ex. mail.example.com, {vHost})


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Sample Data</dt><dd>smtp.gmail.com or {vHost}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Port (ex. 25, 587, {vPort})


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>25 or 587 or {vPort}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Username (ex. myUserName, {vUserName})


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>username or {vUserName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Password (ex. myPassword, {vPassword})


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the SMTP service</dd>
<dt>Sample Data</dt><dd>password or {vPassword}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### From Email (ex. myaccount@example.com, {vMail})


<dl>
<dt>What to input</dt><dd>Specify how the 'From' field should appear.</dd>
<dt>Sample Data</dt><dd>myRobot@company.com or {vMail}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### To Email (ex. toaccount@exmaple.com, {vMail})


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Data</dt><dd>jason@company.com or {vMail}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Subject (ex. Alert Mail, {vTitle})


<dl>
<dt>What to input</dt><dd>Define the text subject (or variable) that the email should have.</dd>
<dt>Sample Data</dt><dd>Alert! or {vStatus}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_7"></a>
### Body (ex. Everything ok, {vMailMessage})


<dl>
<dt>What to input</dt><dd>Specify the message that should be sent.</dd>
<dt>Sample Data</dt><dd>Everything ran ok at {DateTime.Now}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_8"></a>
### Optional - Attachment Path (ex. C:\temp\file.txt, {vPath})


<dl>
<dt>What to input</dt><dd>Indicates the file path to attachment.</dd>
<dt>Sample Data</dt><dd>c:\temp\file.txt or {vPath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_9"></a>
### Indicate if SSL should be used


<dl>
<dt>What to input</dt><dd>Select from one of the options</dd>
<dt>Sample Data</dt><dd>Yes or No</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_10"></a>
### SSL Validation


<dl>
<dt>What to input</dt><dd>Select the appropriate option</dd>
<dt>Sample Data</dt><dd>Select from Validate SSL, Bypass SSL Validation</dd>
<dt>Remarks</dt><dd>This field manages whether taskt will attempt to validate the SSL connection</dd>
</dl>




<a id="param_11"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SMTPSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
