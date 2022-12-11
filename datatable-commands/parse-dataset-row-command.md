<!--TITLE: Parse Dataset Row Command -->
<!-- SUBTITLE: a command in the DataTable Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DataTable Commands &gt; Other &gt; Parse Dataset Row


# Parse Dataset Row Command


## What does this command do?
This command allows you to parse a dataset row column into a variable.


## When would I want to use this command?
Use this command when you want to extract data from a dataset variable


## Command Parameters
- [Supply the name of the variable containing the datasource](#param_0)
- [Please Select Column Parse Type](#param_1)
- [Specify Column Name or Index](#param_2)
- [Please select the variable to receive the extracted column data](#param_3)
- [Optional - Specify Alternate Row Number](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Supply the name of the variable containing the datasource


<dl>
<dt>What to input</dt><dd>Select or provide a variable</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Select Column Parse Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>By Column Name</strong> or  <strong>By Column Index</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Specify Column Name or Index


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please select the variable to receive the extracted column data


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Optional - Specify Alternate Row Number


<dl>
<dt>What to input</dt><dd>If not executing within a loop, select the applicable index of the row required</dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>vRowNumber</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ParseDatasetRowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
