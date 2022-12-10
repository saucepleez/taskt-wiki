<!--TITLE: Ping Command Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Misc Commands &gt; Network/Internet &gt; Ping Command


# Ping Command Command


## What does this command do?
This command allows you to add an in-line comment to the script.


## When would I want to use this command?
Use this command when you want to add code comments or document code.  Usage of variables (ex. [vVar]) within the comment block will be parsed and displayed when running the script.


## Command Parameters
- [Please Enter ip address or host name that you want to ping (ex. 192.168.0.1, {vHost})](#param_0)
- [Apply Result To Variable](#param_1)
- [Comment Field (Optional)](#param_2)


<a id="param_0"></a>
### Please Enter ip address or host name that you want to ping (ex. 192.168.0.1, {vHost})


<dl>
<dt>What to input</dt><dd>Ip address or hostname you want to ping</dd>
<dt>Sample Data</dt><dd>192.168.0.1 or www.google.com or {vHost}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Apply Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_2"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: PingCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
