<!--TITLE: Create Color From HEX Command -->
<!-- SUBTITLE: a command in the Color Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Color Commands &gt; Create Color From HEX


# Create Color From HEX Command


## What does this command do?
This command allows you to create Color from HEX.


## When would I want to use this command?
Use this command when you want to create Color from HEX.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Color Variable Name](#param_0)
- [Please Specify the Color HEX Value](#param_1)
- [Optional - Please Specify the Comment Field](#param_2)


<a id="param_0"></a>
### Please Select the Color Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Color Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vColor or {vColor}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vColor</strong> | Specify Value of Variable **vColor** |
| <strong>{vColor}</strong> | Specify Value of Variable **vColor** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Color HEX Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>#ff22bb or ff22bb or {vHex}</dd>
<dt>Remarks</dt><dd>Please specify a 6-digit Hexadecimal number</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>#ff22bb</strong> | Specify Hex Value **ff22bb** |
| <strong>ff22bb</strong> | Specify Hex Value **ff22bb** |
| <strong>{vHex}</strong> | Specify Value of Variable **vHex** for HEX Value |


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
Automation Class Name: CreateColorFromHexCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
