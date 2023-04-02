<!--TITLE: Load Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Dictionary Commands &gt; Dictionary Action &gt; Load Dictionary


# Load Dictionary Command


## What does this command do?
This command Reads a Config file and stores it into a Dictionary.


## When would I want to use this command?
Use this command when you want to load a config file.


<a id="param_list"></a>
## Command Parameters
- [Please Enter the Dictionary Variable Name](#param_0)
- [Please indicate the Workbook File Path](#param_1)
- [Please indicate the Sheet Name](#param_2)
- [Please indicate the Key Column](#param_3)
- [Please indicate the Value Column](#param_4)
- [Optional - Please Specify the Comment Field](#param_5)


<a id="param_0"></a>
### Please Enter the Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter a name for a Dictionary.</dd>
<dt>Value</dt><dd>Dictionary Variable</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>myDictionary</strong> or <strong>{vDictionary}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please indicate the Workbook File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file that should be loaded into the Dictionary.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>C:\temp\myfile.xlsx</strong> or <strong>{vFilePath}</strong></dd>
<dt>Remarks</dt><dd>If file does not contain extension, supplement extensions supported by Excel.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please indicate the Sheet Name


<dl>
<dt>What to input</dt><dd>Enter the sheet name of the workbook to be read.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Sheet1</strong> or <strong>{vSheet}</strong></dd>
<dt>Remarks</dt><dd>Sheet has one table</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please indicate the Key Column


<dl>
<dt>What to input</dt><dd>Enter the key column name to create a Dictionary off of.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Key</strong> or <strong>{vKeyColumn}</strong></dd>
<dt>Remarks</dt><dd>This value is NOT Column Index Value like A, B. Please specify table column name.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please indicate the Value Column


<dl>
<dt>What to input</dt><dd>Enter a value column name to create a Dictionary off of.</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Value</strong> or <strong>{vValueColumn}</strong></dd>
<dt>Remarks</dt><dd>This value is NOT Column Index Value like A, B. Please specify table column name.</dd>
</dl>




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
Automation Class Name: LoadDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
