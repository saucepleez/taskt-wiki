<!--TITLE: Loop Complex Data Types Command -->
<!-- SUBTITLE: a command in the Loop group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Loop &gt; Loop Complex Data Types


# Loop Complex Data Types Command


## What does this command do?
This command allows you to Repeat actions on the values held by List, Dictioanry, and other data. This command must have a following 'End Loop' command.


## When would I want to use this command?
Use this command when you want to iterate over each item in a list, or a series of items.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Variable Name or Value to Loop](#param_0)
- [Optional - Please Specify the Comment Field](#param_1)


<a id="param_0"></a>
### Please Specify the Variable Name or Value to Loop


<dl>
<dt>What to input</dt><dd>Enter a variable which contains a list of items</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>{vList} or [1,2,3]</dd>
<dt>Remarks</dt><dd>Use this command to iterate over the results of the Split command.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>{vList}</strong> | Specify Variable Name **vList** |
| <strong>[1,2,3]</strong> | Specify **[1,2,3]** |


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
Automation Class Name: BeginLoopForComplexDataTypesCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
