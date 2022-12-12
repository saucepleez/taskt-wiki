<!--TITLE: Format DateTime Command -->
<!-- SUBTITLE: a command in the DateTime Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime Commands &gt; Format DateTime


# Format DateTime Command


## What does this command do?
This command allows you to Format DateTime Text.


## When would I want to use this command?
Use this command when you want to Format DateTime Text.


## Command Parameters
- [Please Select the Please select a DateTime Variable Name](#param_0)
- [Please Specify the Please specify DateTime Format](#param_1)
- [Please Select the Please specify Variable Name to store Result](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Select the Please select a DateTime Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>DateTime</dd>
<dt>Parameter Direction</dt><dd>Input</dd><dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>{vDateTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please Specify the Please specify DateTime Format


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>MM/dd/yyyy</strong> or <strong>HH:mm:ss</strong> or <strong>{vFormat}</strong></dd>
<dt>Remarks</dt><dd>Please refer to the Microsoft DateTime.ToString() page for format details</dd>
</dl>




<a id="param_2"></a>
### Please Select the Please specify Variable Name to store Result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>vResult</strong> or <strong>{vResult}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: FormatDateTimeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
