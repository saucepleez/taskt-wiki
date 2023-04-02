<!--TITLE: Convert List To Dictionary Command -->
<!-- SUBTITLE: a command in the List Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


List Commands &gt; Convert &gt; Convert List To Dictionary


# Convert List To Dictionary Command


## What does this command do?
This command convert a List to Dictionary.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the List Variable Name](#param_0)
- [Optional - Please Select the Dictionary Keys Type](#param_1)
- [Optional - Please Select the Dictionary Keys Name List or Key Names](#param_2)
- [Optional - Please Select the When the number of items in the List is greater than the number of Keys](#param_3)
- [Optional - Please Select the When the number of Keys is greater than the number of items in the List](#param_4)
- [Please Select the Dictionary Variable Name](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Select the List Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the List Variable Name</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vList</strong> or <strong>{vList}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vList</strong> | Specify Variable Name **vList** |
| <strong>{vList}</strong> | Specify Variable Name **vList** |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Select the Dictionary Keys Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>List</strong> or  <strong>Comma Separated</strong> or  <strong>Space Separated</strong> or  <strong>Tab Separated</strong> or  <strong>NewLine Separated</strong> or  <strong>Key Prefix</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Key Prefix</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>List</strong> | Specify the List Variable Name |
| <strong>Comman Separated</strong> | Enter like **A,B,C** |
| <strong>Space Separated</strong> | Enter like **A B C** |
| <strong>Tab Separated</strong> | Enter like **A	B	C** |
| <strong>item</strong> | When Select **Key Prefix** and Enter **item**, Key Name is item0, item1, item2, ... |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Dictionary Keys Name List or Key Names


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>List</dd>
<dt>Sample Usage</dt><dd>{vColumns} or <strong>A,B,C</strong></dd>
<dt>Remarks</dt><dd>When keys is empty, Dictionary key is item0, item1, ...<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| {vColumns} | Specify List Variable Name **vColumns** |
| <strong>A,B,C</strong> | Specify Column Names **A**, **B**, and **C** As **Comma Separate** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the When the number of items in the List is greater than the number of Keys


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong> or  <strong>Try Create Keys</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the When the number of Keys is greater than the number of items in the List


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Ignore</strong> or  <strong>Error</strong> or  <strong>Insert Empty Value</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Ignore</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Select the Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Dictionary Variable Name</dd>
<dt>Value</dt><dd>Dictionary Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vDictionary</strong> or <strong>{vDictionary}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vDictionary</strong> | Specify Variable Name **vDictionary** |
| <strong>{vDictionary}</strong> | Specify Variable Name **vDictionary** |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: ConvertListToDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
