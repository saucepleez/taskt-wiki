<!--TITLE: Remote Task Command -->
<!-- SUBTITLE: a command in the Remote Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Remote Commands &gt; Remote Task


# Remote Task Command


## What does this command do?
This command allows you to execute a task remotely on another taskt instance


## When would I want to use this command?
Use this command when you want to execute a command on another client that has local listener enabled


<a id="param_list"></a>
## Command Parameters
- [Please enter the IP:Port (ex. 192.168.2.200:19312)](#param_0)
- [Please Select Parameter Type](#param_1)
- [Please Select the Execution Preference](#param_2)
- [Please Specify the Script Parameter Data](#param_3)
- [Please Specify the Request Timeout (ms)](#param_4)
- [Please select the variable to receive the response](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please enter the IP:Port (ex. 192.168.2.200:19312)


<dl>
<dt>What to input</dt><dd>Define any IP endpoint which is enabled for local listening.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select Parameter Type


<dl>
<dt>What to input</dt><dd>Select the necessary parameter.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Run Raw Script Data</strong> or  <strong>Run Local File</strong> or  <strong>Run Remote File</strong> or  <strong>Run Command Json</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Execution Preference


<dl>
<dt>What to input</dt><dd>Select the necessary execution preference.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Continue Execution</strong> or  <strong>Await For Result</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Script Parameter Data


<dl>
<dt>What to input</dt><dd>Specify the data, typically either raw data, local file, or remote file</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the Request Timeout (ms)


<dl>
<dt>What to input</dt><dd>Enter the length of time to wait before the request times out</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please select the variable to receive the response


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: RemoteTaskCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/04/23 01:28 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
