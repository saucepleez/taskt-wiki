<!--TITLE: Convert List To DataTable Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List Commands &gt; Convert &gt; Convert List To DataTable


# Convert List To DataTable Command


## What does this command do?
This command convert a List to a DataTable.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the Supply the List to convert](#param_0)
- [Optional - Please Select DataTable Columns Type](#param_1)
- [Optional - Please Select the Supply the DataTable Columns Name List](#param_2)
- [Optional - Please Select the When the number of items in the List is greater than the number of Columns](#param_3)
- [Optional - Please Select the When the number of Columns is greater than the number of items in the List](#param_4)
- [Please select the variable to receive the DataTable](#param_5)
- [Please Specify the Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please Select the Supply the List to convert


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vList</strong> or <strong>{vList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select DataTable Columns Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>List</strong> or  <strong>Comma Separated</strong> or  <strong>Space Separated</strong> or  <strong>Tab Separated</strong> or  <strong>NewLine Separated</strong> or  <strong>Column Prefix</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Column Prefix</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Supply the DataTable Columns Name List


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Sample Usage</dt><dd><strong>vColumns</strong> or <strong>{vColumns}</strong></dd>
<dt>Remarks</dt><dd>If Columns is empty, DataTable column is column0, column1, ...<br><br>
<strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When the number of items in the List is greater than the number of Columns


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong> or  <strong>Try Create Columns</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the When the number of Columns is greater than the number of items in the List


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong> or  <strong>Insert Empty Value</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please select the variable to receive the DataTable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ConvertListToDataTableCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
