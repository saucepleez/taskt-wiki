<!--TITLE: Send Outlook Email Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Outlook Commands &gt; Send Outlook Email


# Send Outlook Email Command


## What does this command do?
This command allows you to send emails with outlook


## When would I want to use this command?
Use this command when you want to send emails with your currenty logged in outlook account


## Command Parameters
- [Please Indicate Recipients (; delimited)](#param_0)
- [Attachment File Path (Optional)](#param_1)
- [Provide Email Subject](#param_2)
- [Provide Email Body](#param_3)
- [Select Email Body Type](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Indicate Recipients (; delimited)


<dl>
<dt>What to input</dt><dd>Enter the Email Addresses of the recipients in semicolon seperated values</dd>
<dt>Sample Data</dt><dd>test@test.com;test2@test.com</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Attachment File Path (Optional)


<dl>
<dt>What to input</dt><dd>Enter the Filepath of the file you want attached.</dd>
<dt>Sample Data</dt><dd>c:sales reportsy06q4.xlsx</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Provide Email Subject


<dl>
<dt>What to input</dt><dd>Enter the subject you want sent in your Email</dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Provide Email Body


<dl>
<dt>What to input</dt><dd>Enter the body you want on your email to be sent.</dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Select Email Body Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Plain</strong> or  <strong>HTML</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookEmailCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
