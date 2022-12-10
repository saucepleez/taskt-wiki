<!--TITLE: Load Dictionary Command -->
<!-- SUBTITLE: a command in the Dictionary Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Dictionary Commands &gt; Dictionary Action &gt; Load Dictionary


# Load Dictionary Command


## What does this command do?
This command Reads a Config file and stores it into a Dictionary.


## When would I want to use this command?
Use this command when you want to load a config file.


## Command Parameters
- [Please Enter the Dictionary Variable Name](#param_0)
- [Please indicate the Workbook File Path](#param_1)
- [Please indicate the Sheet Name](#param_2)
- [Please indicate the Key Column](#param_3)
- [Please indicate the Value Column](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the Dictionary Variable Name


<dl>
<dt>What to input</dt><dd>Enter a name for a Dictionary.</dd>
<dt>Sample Data</dt><dd>myDictionary or {vDictionary}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the Workbook File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file that should be loaded into the Dictionary.</dd>
<dt>Sample Data</dt><dd>C:\temp\myfile.xlsx or {vFilePath}</dd>
<dt>Remarks</dt><dd>If file does not contain extension, supplement extensions supported by Excel.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_2"></a>
### Please indicate the Sheet Name


<dl>
<dt>What to input</dt><dd>Enter the sheet name of the workbook to be read.</dd>
<dt>Sample Data</dt><dd>Sheet1 or {vSheet}</dd>
<dt>Remarks</dt><dd>Sheet has one table</dd>
</dl>




<a id="param_3"></a>
### Please indicate the Key Column


<dl>
<dt>What to input</dt><dd>Enter the key column name to create a Dictionary off of.</dd>
<dt>Sample Data</dt><dd>Key or {vKeyColumn}</dd>
<dt>Remarks</dt><dd>This value is NOT Column Index Value like A, B. Please specify table column name.</dd>
</dl>




<a id="param_4"></a>
### Please indicate the Value Column


<dl>
<dt>What to input</dt><dd>Enter a value column name to create a Dictionary off of.</dd>
<dt>Sample Data</dt><dd>Value or {vValueColumn}</dd>
<dt>Remarks</dt><dd>This value is NOT Column Index Value like A, B. Please specify table column name.</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: LoadDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
