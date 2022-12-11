<!--TITLE: Get EMail Text Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Get EMail Text


# Get EMail Text Command


## What does this command do?
This command allows you to get Text from EMail.


## When would I want to use this command?
Use this command when you want to get Text from EMail.


## Command Parameters
- [Please specify EMail Variable Name](#param_0)
- [Please specify Address Type](#param_1)
- [Please specify Variable Name to Store Text](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify EMail Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>MailKitEMail</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vEMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify Address Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>Message Body</strong> or  <strong>Text Message Body</strong> or  <strong>HTML Message Body</strong> or  <strong>Subject</strong> or  <strong>Message-ID</strong> or  <strong>Date</strong> or  <strong>Resent-Message-ID</strong> or  <strong>Resent-Date</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please specify Variable Name to Store Text


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vText</strong> or <strong>{vText}</strong></dd>
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
Automation Class Name: MailKitGetEMailTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
