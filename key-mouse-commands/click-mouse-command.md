<!--TITLE: Click Mouse Command -->
<!-- SUBTITLE: a command in the Key/Mouse Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Key/Mouse Commands &gt; Mouse &gt; Click Mouse


# Click Mouse Command


## What does this command do?
Simulates mouse clicks.


## When would I want to use this command?
Use this command to simulate multiple types of mouse clicks.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Mouse Click Type](#param_0)
- [Optional - Please Specify the Wait Time after Mouse Click (ms)](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the Mouse Click Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Left Click</strong> or  <strong>Middle Click</strong> or  <strong>Right Click</strong> or  <strong>Left Down</strong> or  <strong>Middle Down</strong> or  <strong>Right Down</strong> or  <strong>Left Up</strong> or  <strong>Middle Up</strong> or  <strong>Right Up</strong> or  <strong>Double Left Click</strong> or  <strong>None</strong></dd>
<dt>Remarks</dt><dd>You can simulate custom click by using multiple mouse click commands in succession, adding <strong>Pause Command</strong> in between where required.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Wait Time after Mouse Click (ms)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>500</strong> or <strong>{vWaitTime}</strong></dd>
<dt>Remarks</dt><dd>When the Wait Time is less than <strong>100</strong> is specified, it will be <strong>100</strong><br><br>
<strong>Optional</strong><br>Default Value is <strong>500</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>500</strong> | Specify **500** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ClickMouseCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 07/23/23 01:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
