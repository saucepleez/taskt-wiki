<!--TITLE: Convert Color Command -->
<!-- SUBTITLE: a command in the Color Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Color Commands &gt; Convert Color


# Convert Color Command


## What does this command do?
This command allows you to get convert Color Value.


## When would I want to use this command?
Use this command when you want to get convert Color Value.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Color Variable Name](#param_0)
- [Please Select the Color Format](#param_1)
- [Please Select the Variable Name to Store Result](#param_2)
- [Optional - Please Specify the Comment Field](#param_3)


<a id="param_0"></a>
### Please Select the Color Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>Color</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>{vColor}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>{vColor}</strong> | Specify Value of Variable **vColor** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Color Format


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Hex</strong> or  <strong>CSS RGB</strong> or  <strong>CSS RGBA</strong> or  <strong>Excel Color</strong> or  <strong>Red</strong> or  <strong>Green</strong> or  <strong>Blue</strong> or  <strong>Alpha</strong> or  <strong>HSL</strong> or  <strong>CMYK</strong> or  <strong>RGBA Dictionary</strong> or  <strong>RGBA DataTable</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>


#### Addtional Info about &quot;Please Select the Color Format&quot;
| Parameter Value(s) | Description   | Sample Data 	| Remarks  	|
| ---             | ---           | ---          | ---       |
|Hex|Convert to Hex value, like **11FFAA**|||
|CSS RGB|Convert to CSS RGB value, like **rgb(255, 64, 0)**|||
|CSS RGBA|Convert to CSS RGB value, like **rgba(255, 64, 0, 0.6)**|||
|Excel Color|Convert to Excel Color Value like **25312**|||
|RGBA Dictionary|Convert to Dictionary. Key names are R, G, B, A.|||
|RGBA DataTable|Convert to DataTable. Column names are R, G, B, A.|||


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ConvertColorCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 03/02/24 04:01 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
