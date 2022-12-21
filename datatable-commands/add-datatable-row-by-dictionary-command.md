<!--TITLE: Add DataTable Row By Dictionary Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Row Action &gt; Add DataTable Row By Dictionary


# Add DataTable Row By Dictionary Command


## What does this command do?
This command allows you to add a DataTable Row to a DataTable by a Dictionary


## When would I want to use this command?
Use this command when you want to add a DataTable Row to a DataTable by a Dictionary.


<a id="param_list"></a>
## Command Parameters
- [Please indicate the DataTable Variable Name to be added a row](#param_0)
- [Please specify the Dictionary Variable Name to add to the DataTable](#param_1)
- [Optional - Please specify the if Dictionary key does not exists](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please indicate the DataTable Variable Name to be added a row


<dl>
<dt>What to input</dt><dd>Enter a existing DataTable Variable Name</dd>
<dt>Instance Type</dt><dd>DataTable</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>myDataTable</strong> or <strong>{vMyDataTable}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify the Dictionary Variable Name to add to the DataTable


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>Dictionary</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please specify the if Dictionary key does not exists


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: AddDataTableRowByDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
