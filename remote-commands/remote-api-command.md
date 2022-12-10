<!--TITLE: Remote API Command -->
<!-- SUBTITLE: a command in the Remote Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Remote Commands &gt; Remote API


# Remote API Command


## What does this command do?
This command allows you to execute automation against another taskt Client.


## When would I want to use this command?
Use this command when you want to automate against a taskt instance that enables Local Listener.


## Command Parameters
- [Please enter the IP:Port (ex. 192.168.2.200:19312)](#param_0)
- [Select Parameter Type](#param_1)
- [Request Timeout (ms)](#param_2)
- [Please select the variable to receive the response](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please enter the IP:Port (ex. 192.168.2.200:19312)


<dl>
<dt>What to input</dt><dd>Define any IP endpoint which is enabled for local listening.</dd>
<dt>Sample Data</dt><dd>https://example.com or {vMyUrl}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Select Parameter Type


<dl>
<dt>What to input</dt><dd>Select the necessary API Method</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Request Timeout (ms)


<dl>
<dt>What to input</dt><dd>Enter the length of time to wait before the request times out </dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the response


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RemoteAPICommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
