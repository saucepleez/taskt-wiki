<!--TITLE: File Dialog Command -->
<!-- SUBTITLE: a command in the Input Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Input Commands &gt; File Dialog


# File Dialog Command


## What does this command do?
Show OpenFileDialog or SaveFileDialog


## When would I want to use this command?
Use this command when you want to select file to save or open.


## Command Parameters
- [Specify the type of dialog](#param_0)
- [Specify the value of the Filter property](#param_1)
- [Optional - Specify the value of the FilterIndex property (Default is 1)](#param_2)
- [Optional - Specify the value of the InitialDirectory property (Default is documents)](#param_3)
- [Please select the variable to receive file name](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Specify the type of dialog


<dl>
<dt>What to input</dt><dd>OpenFileDialog or SaveFileDialog</dd>
<dt>Sample Data</dt><dd>Open or Save</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Specify the value of the Filter property


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Text File (*.txt)|*.txt or {vFilter}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Specify the value of the FilterIndex property (Default is 1)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>1 or 2 or {vIndex}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Specify the value of the InitialDirectory property (Default is documents)


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>C:\Users\myUser\Documents or {vFolderPath}</dd>
<dt>Remarks</dt><dd><b>Optional</b><br></dd>
</dl>




<a id="param_4"></a>
### Please select the variable to receive file name


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: FileDialogCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
