<!--TITLE: Get Window Position Command -->
<!-- SUBTITLE: a command in the Window Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Window Commands &gt; Window State &gt; Get Window Position


# Get Window Position Command


## What does this command do?
This command returns window position.


## When would I want to use this command?
Use this command when you want window position.


## Command Parameters
- [Please enter or select the window position that you want to.](#param_0)
- [Optional - Window title search method](#param_1)
- [Optional - Specify the variable to recieve the window position X](#param_2)
- [Optional - Specify the variable to recieve the window position Y](#param_3)
- [Optional - Base position](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please enter or select the window position that you want to.


<dl>
<dt>What to input</dt><dd>Input or Type the name of the window name that you want to.</dd>
<dt>Sample Data</dt><dd>Untitled - Notepad or Current Window or {vWindow}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Window title search method


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>Contains or Starts with or Ends with or Exact match</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Contains</dd>
</dl>




<a id="param_2"></a>
### Optional - Specify the variable to recieve the window position X


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.<b>Optional</b><br></dd>
</dl>




<a id="param_3"></a>
### Optional - Specify the variable to recieve the window position Y


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.<b>Optional</b><br></dd>
</dl>




<a id="param_4"></a>
### Optional - Base position


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><b>Optional</b><br>Default Value is Top Left</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: GetWindowPositionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
