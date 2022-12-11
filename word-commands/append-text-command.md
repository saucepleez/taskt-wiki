<!--TITLE: Append Text Command -->
<!-- SUBTITLE: a command in the Word Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Word Commands &gt; Append Text


# Append Text Command


## What does this command do?
This command appends text to a word document.


## When would I want to use this command?
Use this command when you want to append text to a specific document.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Enter the Text Variable Name to Set](#param_1)
- [Select or Enter the text font name](#param_2)
- [Select or Enter the text font size](#param_3)
- [Select Bold](#param_4)
- [Select Italic](#param_5)
- [Select Underline](#param_6)
- [Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Word</strong> command</dd>
<dt>Instance Type</dt><dd>Word</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>wordInstance</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Word</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Enter the Text Variable Name to Set


<dl>
<dt>What to input</dt><dd>Enter the text value that will be set.</dd>
<dt>Sample Data</dt><dd>Hello World or {vText}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Select or Enter the text font name


<dl>
<dt>What to input</dt><dd>Specify the font name.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Arial</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Select or Enter the text font size


<dl>
<dt>What to input</dt><dd>Specify the font name.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>14</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Select Bold


<dl>
<dt>What to input</dt><dd>Specify whether the text font should be bold.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Select Italic


<dl>
<dt>What to input</dt><dd>Specify whether the text font should be italic.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Select Underline


<dl>
<dt>What to input</dt><dd>Specify whether the text font should be underlined.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Yes</strong> or <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: WordAppendTextCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
