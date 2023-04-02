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
- [Please Select the Color Variable Name](#param_0)
- [Please Specify the Red Value](#param_1)
- [Please Specify the Green Value](#param_2)
- [Please Specify the Blue Value](#param_3)
- [Optional - Please Specify the Alpha Value](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Select the Color Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Color Variable</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vColor</strong> or <strong>{vColor}</strong></dd>
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
### Please Specify the Red Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>255</strong> or <strong>{vRed}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify value **0**. **0** is min value of range |
| <strong>255</strong> | Specify value **255**. **255** is max value of range |
| <strong>{vRed}</strong> | Specify Value of Variable **vRed** for Red |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Green Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>255</strong> or <strong>{vGreen}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify value **0**. **0** is min value of range |
| <strong>255</strong> | Specify value **255**. **255** is max value of range |
| <strong>{vGreen}</strong> | Specify Value of Variable **vGreen** for Green |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Blue Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>255</strong> or <strong>{vBlue}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify value **0**. **0** is min value of range |
| <strong>255</strong> | Specify value **255**. **255** is max value of range |
| <strong>{vBlue}</strong> | Specify Value of Variable **vBlue** for Blue |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Alpha Value


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li><strong>Not</strong> Between 0 to 255</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>255</strong> or <strong>{vAlpha}</strong></dd>
<dt>Remarks</dt><dd>Values range from 0 to 255<br><br>
<strong>Optional</strong><br>Default Value is <strong>255</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify value **0**. **0** is min value of range |
| <strong>255</strong> | Specify value **255**. **255** is max value of range |
| <strong>{vAlpha}</strong> | Specify Value of Variable **vAlpha** for Alpha |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: CreateColorCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
