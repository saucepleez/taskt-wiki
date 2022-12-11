<!--TITLE: Move/Copy Outlook Emails Command -->
<!-- SUBTITLE: a command in the Outlook Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Outlook Commands &gt; Move/Copy Outlook Emails


# Move/Copy Outlook Emails Command


## What does this command do?
This command allows you to move/copy emails with outlook


## When would I want to use this command?
Use this command when you want to move/copy emails with your currenty logged in outlook account


## Command Parameters
- [Indicate whether to Move or Copy the emails](#param_0)
- [Provide the source mail folder name](#param_1)
- [Provide a filter (Optional)](#param_2)
- [Move/Copy unread emails only](#param_3)
- [Provide the destination folder name](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Indicate whether to Move or Copy the emails


<dl>
<dt>What to input</dt><dd>Specify whether you intend to move or copy the Emails. Moving will remove the emails from the original folder while Copying will not.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select either <strong>Move Emails</strong> or <strong>Copy Emails</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Provide a filter (Optional)


<dl>
<dt>What to input</dt><dd>[Subject] = 'Hello' and [SenderName] = 'Jane Doe'</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>[Subject] = 'Hello'</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Move/Copy unread emails only


<dl>
<dt>What to input</dt><dd>Specify whether to move/copy unread email messages only</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Provide the destination folder name


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the directory.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>myData</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookMoveEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
