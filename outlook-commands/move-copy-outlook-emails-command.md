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
- [Please Select the Indicate whether to Move or Copy the emails](#param_0)
- [Please Specify the Provide the source mail folder name](#param_1)
- [Please Specify the Provide a filter (Optional)](#param_2)
- [Please Select the Move/Copy unread emails only](#param_3)
- [Please Specify the Provide the destination folder name](#param_4)
- [Please Specify the Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Select the Indicate whether to Move or Copy the emails


<dl>
<dt>What to input</dt><dd>Specify whether you intend to move or copy the Emails. Moving will remove the emails from the original folder while Copying will not.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Move Emails</strong> or  <strong>Copy Emails</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Specify the Provide the source mail folder name


<dl>
<dt>What to input</dt><dd>Enter the mail folder you want your emails to come from</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify the Provide a filter (Optional)


<dl>
<dt>What to input</dt><dd>[Subject] = 'Hello' and [SenderName] = 'Jane Doe'</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Select the Move/Copy unread emails only


<dl>
<dt>What to input</dt><dd>Specify whether to move/copy unread email messages only</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please Specify the Provide the destination folder name


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the directory.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: OutlookMoveEmailsCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
