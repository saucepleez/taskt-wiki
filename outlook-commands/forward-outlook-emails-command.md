<!--TITLE: Forward Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Outlook Commands &gt; Forward Outlook Emails


# Forward Outlook Emails Command


## What does this command do?
This command allows you to forward emails with outlook


## When would I want to use this command?
Use this command when you want to forward emails with your currenty logged in outlook account


## Command Parameters
- [Provide the source mail folder name](#param_0)
- [Provide a filter (Optional)](#param_1)
- [Indicate Recipients (; delimited)](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt>Sample Data</dt><dd>myData</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Provide a filter (Optional)


<dl>
<dt>What to input</dt><dd>Enter an outlook filter string</dd>
<dt>Sample Data</dt><dd>[Subject] = 'Hello' and [SenderName] = 'Jane Doe'</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Indicate Recipients (; delimited)


<dl>
<dt>What to input</dt><dd>Enter the Email Addresses of the recipients in semicolon seperated values</dd>
<dt>Sample Data</dt><dd>test@test.com;test2@test.com</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookForwardEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
