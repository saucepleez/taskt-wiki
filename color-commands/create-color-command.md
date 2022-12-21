<!--TITLE: Create Color Command -->
<!-- SUBTITLE: a command in the Color Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Color Commands &gt; Create Color


# Create Color Command


## What does this command do?
This command allows you to create Color.


## When would I want to use this command?
Use this command when you want to create Color.


<a id="param_list"></a>
## Command Parameters
- [Please select a Color Variable Name](#param_0)
- [Please specify Red Value](#param_1)
- [Please specify Green Value](#param_2)
- [Please specify Blue Value](#param_3)
- [Optional - Please specify Alpha Value](#param_4)
- [Please Specify the Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please select a Color Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vColor</strong> or <strong>{vColor}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify Red Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <em>255</em>* or <strong>{vRed}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please specify Green Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <em>255</em>* or <strong>{vGreen}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please specify Blue Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <em>255</em>* or <strong>{vBlue}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please specify Alpha Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <em>255</em>* or <strong>{Alpha}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255<br><br>
<strong>Optional</strong><br>Default Value is <strong>255</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CreateColorCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
