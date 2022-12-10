<!--TITLE: Recieve EMailList Using IMAP Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
EMail Commands &gt; Recieve EMailList Using IMAP


# Recieve EMailList Using IMAP Command


## What does this command do?
This command allows you to get EMailList(Emails) using IMAP protocol.


## When would I want to use this command?
Use this command when you want to get EMailList(Emails) using IMAP protocol. Result Variable Type is EMailList.


## Command Parameters
- [Please specify IMAP Host Name](#param_0)
- [Please specify IMAP Port](#param_1)
- [Please specify IMAP Username](#param_2)
- [Please specify IMAP Password](#param_3)
- [Optional - Please specify Secure Option](#param_4)
- [Please specify Variable Name to Store EMailList](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please specify IMAP Host Name


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Sample Data</dt><dd>imap.mymail.com or {vHost}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify IMAP Port


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the IMAP service</dd>
<dt>Sample Data</dt><dd>143 or 993 or {vPort}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please specify IMAP Username


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the IMAP service</dd>
<dt>Sample Data</dt><dd>username or {vUserName}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify IMAP Password


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the IMAP service</dd>
<dt>Sample Data</dt><dd>password or {vPassword}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Optional - Please specify Secure Option


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Auto</dd>
</dl>




<a id="param_5"></a>
### Please specify Variable Name to Store EMailList


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vMailList or {vMailList}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MailKitRecieveEmailListUsingIMAPCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
