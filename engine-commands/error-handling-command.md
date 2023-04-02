<!--TITLE: Error Handling Command -->
<!-- SUBTITLE: a command in the Engine Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Engine Commands &gt; Error Handling


# Error Handling Command


## What does this command do?
This command specifies what to do  after an error is encountered.


## When would I want to use this command?
Use this command when you want to define how your script should behave when an error is encountered.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Action to Take in the Event an Error Occurs](#param_0)
- [Optional - Please Specify the Comment Field](#param_1)


<a id="param_0"></a>
### Please Select the Action to Take in the Event an Error Occurs


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Stop Processing</strong> or  <strong>Continue Processing</strong></dd>
<dt>Remarks</dt><dd><strong>If Command</strong> allows you to specify and test if a line number encountered an error. In order to use that functionality, you must specify <strong>Continue Processing</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Stop Processing</strong> | End the Script if an Error is Encountered |
| <strong>Continue Processing</strong> | Continue Running the Script |
| <strong>{vAction}</strong> | Specify Value of Variable **vAction** for Action |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ErrorHandlingCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
