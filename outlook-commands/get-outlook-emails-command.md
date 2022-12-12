<!--TITLE: Get Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Outlook Commands &gt; Get Outlook Emails


# Get Outlook Emails Command


## What does this command do?
This command allows you to get emails and attachments with outlook


## When would I want to use this command?
Use this command when you want to get emails and attachments with your currenty logged in outlook account


## Command Parameters
- [Please Specify the Provide the source mail folder name](#param_0)
- [Please Specify the Provide a filter (Optional)](#param_1)
- [Please Select the Get unread emails only](#param_2)
- [Please Select the Mark emails as read](#param_3)
- [Please indicate the output directory for the messages](#param_4)
- [Please Specify the Assign MailItem List to variable](#param_5)
- [Please Select the Save messages and attachments](#param_6)
- [Please indicate the output directory for the attachments](#param_7)
- [Please Specify the Comment Field (Optional)](#param_8)


<a id="param_0"></a>
### Please Specify the Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Specify the Provide a filter (Optional)


<dl>
<dt>What to input</dt><dd>Enter an outlook filter string</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Select the Get unread emails only


<dl>
<dt>What to input</dt><dd>Specify whether to retrieve unread email messages only</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Select the Mark emails as read


<dl>
<dt>What to input</dt><dd>Specify whether to retrieve unread email messages only</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please indicate the output directory for the messages


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the directory.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please Specify the Assign MailItem List to variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Please Select the Save messages and attachments


<dl>
<dt>What to input</dt><dd>Specify whether to save the email attachments to a local directory</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_7"></a>
### Please indicate the output directory for the attachments


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the directory.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_8"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookGetEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
