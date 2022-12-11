<!--TITLE: Recieve EMailList Using POP Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Recieve EMailList Using POP


# Recieve EMailList Using POP Command


## What does this command do?
This command allows you to get EMailList(EMails) using POP protocol.


## When would I want to use this command?
Use this command when you want to get MailList(EMails) using POP protocol. Result Variable Type is EMailList.


## Command Parameters
- [Please specify POP Host Name](#param_0)
- [Please specify POP Port](#param_1)
- [Please specify POP Username](#param_2)
- [Please specify POP Password](#param_3)
- [Optional - Please specify Secure Option](#param_4)
- [Please specify Variable Name to Store EMailList](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please specify POP Host Name


<dl>
<dt>What to input</dt><dd>Define the host/service name that the script should use</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>pop.mymail.com</strong> or <strong>{vHost}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify POP Port


<dl>
<dt>What to input</dt><dd>Define the port number that should be used when contacting the POP service</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
</ul></dd><dt>Sample Data</dt><dd><strong>110</strong> or <strong>995</strong> or <strong>{vPort}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please specify POP Username


<dl>
<dt>What to input</dt><dd>Define the username to use when contacting the POP service</dd>
<dt>Sample Data</dt><dd><strong>username</strong> or <strong>{vUserName}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify POP Password


<dl>
<dt>What to input</dt><dd>Define the password to use when contacting the POP service</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>password</strong> or <strong>{vPassword}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Optional - Please specify Secure Option


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Auto</strong> or  <strong>No SSL or TLS</strong> or  <strong>Use SSL or TLS</strong> or  <strong>STARTTLS</strong> or  <strong>STARTTLS When Available</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Auto</strong></dd>
</dl>




<a id="param_5"></a>
### Please specify Variable Name to Store EMailList


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>vMailList</strong> or <strong>{vMailList}</strong></dd>
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
Automation Class Name: MailKitRecieveEmailListUsingPOPCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
