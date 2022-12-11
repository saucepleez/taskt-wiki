<!--TITLE: Extract File Command -->
<!-- SUBTITLE: a command in the File Operation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


File Operation Commands &gt; Extract File


# Extract File Command


## What does this command do?
This command extracts files from a compressed file


## When would I want to use this command?



## Command Parameters
- [Please enter the file path or location](#param_0)
- [Please indicate the extraction folder](#param_1)
- [Optional - Create folder if destination does not exist](#param_2)
- [Optional - Indicate the archive password](#param_3)
- [Optional - Indicate the variable to receive a list of extracted file names](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please enter the file path or location


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file or enter file URL.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\myfile.zip</strong> , <strong>{vFilePath}</strong> or <strong>https://temp.com/myfile.zip</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please indicate the extraction folder


<dl>
<dt>What to input</dt><dd>Enter or Select the path to the applicable file or enter file URL.</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>*<em>C:\temp*</em> or <strong>{vFilePath}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Create folder if destination does not exist


<dl>
<dt>What to input</dt><dd>Specify whether the directory should be created if it does not already exist.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>No</strong></dd>
</dl>




<a id="param_3"></a>
### Optional - Indicate the archive password


<dl>
<dt>What to input</dt><dd>Enter archive files password.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>mypass</strong> or {vPass}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Indicate the variable to receive a list of extracted file names


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.<br><br>
<strong>Optional</strong><br></dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: ExtractFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
