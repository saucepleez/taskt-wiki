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
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Open</strong> or <strong>Save</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Specify the value of the Filter property


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>Text File (*.txt)|*.txt</strong> or <strong>{vFilter}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Specify the value of the FilterIndex property (Default is 1)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>1</strong> or <strong>2</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Specify the value of the InitialDirectory property (Default is documents)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Data</dt><dd><strong>C:\Users\myUser\Documents</strong> or <strong>{vFolderPath}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_4"></a>
### Please select the variable to receive file name


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
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
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
