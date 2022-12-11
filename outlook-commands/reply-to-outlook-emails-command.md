<!--TITLE: Reply To Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Outlook Commands &gt; Reply To Outlook Emails


# Reply To Outlook Emails Command


## What does this command do?
This command allows you to reply to emails with outlook


## When would I want to use this command?
Use this command when you want to reply to emails with your currenty logged in outlook account


## Command Parameters
- [Indicate whether to Reply or Reply All](#param_0)
- [Provide the source mail folder name](#param_1)
- [Provide a filter (Optional)](#param_2)
- [Provide Email Body](#param_3)
- [Select Email Body Type](#param_4)
- [Attachment File Path (Optional)](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Indicate whether to Reply or Reply All


<dl>
<dt>What to input</dt><dd>Specify whether you intend to reply or reply all. Replying will reply to only the original sender. Reply all will reply to everyone.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select either <strong>Reply</strong> or <strong>Reply All</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Provide a filter (Optional)


<dl>
<dt>What to input</dt><dd>Enter an outlook filter string</dd>
<dt>Sample Data</dt><dd>[Subject] = 'Hello' and [SenderName] = 'Jane Doe'</dd>
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
### Attachment File Path (Optional)


<dl>
<dt>What to input</dt><dd>Enter the Filepath of the file you want attached.</dd>
<dt>Sample Data</dt><dd>c:sales reportsy06q4.xlsx</dd>
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
Automation Class Name: OutlookReplyToEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
