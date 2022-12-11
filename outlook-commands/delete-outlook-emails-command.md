<!--TITLE: Delete Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Outlook Commands &gt; Delete Outlook Emails


# Delete Outlook Emails Command


## What does this command do?
This command allows you to delete emails with outlook


## When would I want to use this command?
Use this command when you want to delete emails with your currenty logged in outlook account


## Command Parameters
- [Provide the source mail folder name](#param_0)
- [Provide a filter (Required)](#param_1)
- [Delete read emails only](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Provide a filter (Required)


<dl>
<dt>What to input</dt><dd>Enter an outlook filter string</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>[Subject] = 'Hello' and [SenderName] = 'Jane Doe'</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Delete read emails only


<dl>
<dt>What to input</dt><dd>Specify whether to delete read email messages only</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookDeleteEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
