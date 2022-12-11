<!--TITLE: Get EMail From MailList Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Get EMail From MailList


# Get EMail From MailList Command


## What does this command do?
This command allows you to get EMail from EMailList.


## When would I want to use this command?
Use this command when you want to get EMail from EMailList.


## Command Parameters
- [Please specify EMailList Variable Name](#param_0)
- [Optional - Please specify EMailList Index](#param_1)
- [Please specify Variable Name to Store EMail](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify EMailList Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>MailKitEMailList</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>{vMailList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please specify EMailList Index


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>CurrentPosition</strong></dd>
</dl>




<a id="param_2"></a>
### Please specify Variable Name to Store EMail


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vEMail</strong> or <strong>{vEMail}</strong></dd>
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
Automation Class Name: MailKitGetEMailFromEMailListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
