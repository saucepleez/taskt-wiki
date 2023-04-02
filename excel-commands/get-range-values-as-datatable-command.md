<!--TITLE: Get Range Values As DataTable Command -->
<!-- SUBTITLE: a command in the Excel Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Excel Commands &gt; Range &gt; Get Range Values As DataTable


# Get Range Values As DataTable Command


## What does this command do?
This command get Range values as DataTable.


## When would I want to use this command?
Use this command when you want to get Range values as DataTable.


<a id="param_list"></a>
## Command Parameters
- [Please Select the Excel Instance Name](#param_0)
- [Optional - Please Select the Column Type](#param_1)
- [Please Specify the Start Column Location or Index](#param_2)
- [Optional - Please Specify the End Column Location or Index](#param_3)
- [Please Specify the Start Row Index](#param_4)
- [Optional - Please Specify the End Row Index](#param_5)
- [Please Select the DataTable Variable Name](#param_6)
- [Optional - Please Select the Value Type](#param_7)
- [Optional - Please Specify the Comment Field](#param_8)


<a id="param_0"></a>
### Please Select the Excel Instance Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Excel Instance Name</dd>
<dt>Instance Type</dt><dd>Excel</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>RPAExcel</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Please specify the Excel Instance Name created by <strong>Create Excel Instance</strong> command in advance.</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>RPAExcel</strong> | Specify **RPAExcel** for Excel Instance Name |
| <strong>{vInstance}</strong> | Specify Value of Variable **vInstance** for Excel Instance Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the Column Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Range</strong> or  <strong>RC</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Range</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Range</strong> | Use Range, like **A**. It means first column. |
| <strong>RC</strong> | Use Row-Column, like **1**. It means first column. |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Start Column Location or Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Column Location or Index</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>A</strong> or <strong>1</strong> or <strong>{vColumn}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>A</strong> | Specify the First Column when **Range** is specified for Column Type. |
| <strong>1</strong> | Specify the First Column when **RC** is specified for Column Type. |
| <strong>{vColumn}</strong> | Specify Value of Variable **vColumn** for Column |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Specify the End Column Location or Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Column Location or Index</dd>
<dt>Sample Usage</dt><dd><strong>A</strong> or <strong>1</strong> or <strong>{vColumn}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Last Column</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>A</strong> | Specify the First Column when **Range** is specified for Column Type. |
| <strong>1</strong> | Specify the First Column when **RC** is specified for Column Type. |
| <strong>{vColumn}</strong> | Specify Value of Variable **vColumn** for Column |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the Start Row Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Start Row</dd>
<dt>Sample Usage</dt><dd><strong>1</strong> or <strong>2</strong> or <strong>{vRow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify the First Row Index for Start Row |
| <strong>2</strong> | Specify **2** for Start Row |
| <strong>{vRow}</strong> | Specify Value of Variable **vRow** for Start Row |


<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the End Row Index


<dl>
<dt>What to input</dt><dd>Enter or Select the End Row</dd>
<dt>Sample Usage</dt><dd><strong>1</strong> or <strong>2</strong> or <strong>{vRow}</strong></dd>
<dt>Remarks</dt><dd>When End Row Index is Empty, Automatically specifies the Last Row where values are entered consecutively<br><br>
<strong>Optional</strong><br>Default Value is <strong>Last Row</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>1</strong> | Specify the First Row Index for Start Row |
| <strong>2</strong> | Specify **2** for Start Row |
| <strong>{vRow}</strong> | Specify Value of Variable **vRow** for Start Row |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Select the DataTable Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the DataTable Variable Name</dd>
<dt>Value</dt><dd>DataTable Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vDataTable</strong> or <strong>{vDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDataTable</strong> | Specify Variable Name **vDataTable** |
| <strong>{vDataTable}</strong> | Specify Variable Name **vDataTable** |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Select the Value Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Cell</strong> or  <strong>Formula</strong> or  <strong>Format</strong> or  <strong>Font Color</strong> or  <strong>Back Color</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Cell</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Cell</strong> | Specify the Cell Value |
| <strong>Formula</strong> | Specify the Cell Formula, like **=SUM(A1:A10)** |
| <strong>Format</strong> | Specify the Cell Format |
| <strong>Font Color</strong> | Specify the Cell Text Color |
| <strong>Back Color</strong> | Specify the Cell Background Color |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ExcelGetRangeValuesAsDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
