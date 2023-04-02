<!--TITLE: Send SMTP Email Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Misc Commands &gt; Network/Internet &gt; Send SMTP Email


# Send SMTP Email Command


## What does this command do?
This command allows you to send email using SMTP protocol.


## When would I want to use this command?
Use this command when you want to send an email and have access to SMTP server credentials to generate an email.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Host Name (ex. mail.example.com, {vHost})](#param_0)
- [Please Specify the Port (ex. 25, 587, {vPort})](#param_1)
- [Please Specify the Username (ex. myUserName, {vUserName})](#param_2)
- [Please Specify the Password (ex. myPassword, {vPassword})](#param_3)
- [Please Specify the From Email (ex. myaccount@example.com, {vMail})](#param_4)
- [Please Specify the To Email (ex. toaccount@exmaple.com, {vMail})](#param_5)
- [Please Specify the Subject (ex. Alert Mail, {vTitle})](#param_6)
- [Please Specify the Body (ex. Everything ok, {vMailMessage})](#param_7)
- [Please Specify the Optional - Attachment Path (ex. C:\temp\file.txt, {vPath})](#param_8)
- [Please Indicate if SSL should be used](#param_9)
- [Please Select the SSL Validation](#param_10)
- [Optional - Please Specify the Comment Field](#param_11)


<a id="param_0"></a>
### Please Specify the Host Name (ex. mail.example.com, {vHost})


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Port (ex. 25, 587, {vPort})


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the SMTP service</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Username (ex. myUserName, {vUserName})


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the SMTP service</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Password (ex. myPassword, {vPassword})


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the SMTP service</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the From Email (ex. myaccount@example.com, {vMail})


<dl>
<dt>What to input</dt><dd>Specify how the 'From' field should appear.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the To Email (ex. toaccount@exmaple.com, {vMail})


<dl>
<dt>What to input</dt><dd>Specify the destination email that should be addressed.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Specify the Subject (ex. Alert Mail, {vTitle})


<dl>
<dt>What to input</dt><dd>Define the text subject (or variable) that the email should have.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Please Specify the Body (ex. Everything ok, {vMailMessage})


<dl>
<dt>What to input</dt><dd>Specify the message that should be sent.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Please Specify the Optional - Attachment Path (ex. C:\temp\file.txt, {vPath})


<dl>
<dt>What to input</dt><dd>Indicates the file path to attachment.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Please Indicate if SSL should be used


<dl>
<dt>What to input</dt><dd>Select from one of the options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / [next](#param_10)


</div>


<a id="param_10"></a>
### Please Select the SSL Validation


<dl>
<dt>What to input</dt><dd>Select the appropriate option</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Validate SSL</strong> or  <strong>Bypass SSL Validation</strong></dd>
<dt>Remarks</dt><dd>This field manages whether taskt will attempt to validate the SSL connection</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_10) / [list](#param_list) / [next](#param_11)


</div>


<a id="param_11"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_11) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SMTPSendEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
