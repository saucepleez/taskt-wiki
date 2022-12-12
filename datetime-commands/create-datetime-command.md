<!--TITLE: Create DateTime Command -->
<!-- SUBTITLE: a command in the DateTime Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


DateTime Commands &gt; Create DateTime


# Create DateTime Command


## What does this command do?
This command allows you to create DateTime.


## When would I want to use this command?
Use this command when you want to create DateTime.


## Command Parameters
- [Please Select the Please select a DateTime Variable Name](#param_0)
- [Optional - Please Specify the Please specify Year to set](#param_1)
- [Optional - Please Specify the Please specify Month to set](#param_2)
- [Optional - Please Specify the Please specify Day to set](#param_3)
- [Optional - Please Specify the Please specify Hour to set](#param_4)
- [Optional - Please Specify the Please specify Minute to set](#param_5)
- [Optional - Please Specify the Please specify Second to set](#param_6)
- [Please Specify the Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please Select the Please select a DateTime Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>vDateTime</strong> or <strong>{vDateTime}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Optional - Please Specify the Please specify Year to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>2000</strong> or <strong>{vYear}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




<a id="param_2"></a>
### Optional - Please Specify the Please specify Month to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
<li><strong>Not</strong> Between 1 to 12</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vMonth}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




<a id="param_3"></a>
### Optional - Please Specify the Please specify Day to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li>Equals Zero</li>
<li><strong>Not</strong> Between 1 to 31</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vDay}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>1</strong></dd>
</dl>




<a id="param_4"></a>
### Optional - Please Specify the Please specify Hour to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li><strong>Not</strong> Between 0 to 23</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vHour}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




<a id="param_5"></a>
### Optional - Please Specify the Please specify Minute to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li><strong>Not</strong> Between 0 to 59</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vMinute}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




<a id="param_6"></a>
### Optional - Please Specify the Please specify Second to set


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
<li><strong>Not</strong> Between 0 to 59</li>
</ul></dd><dt>Sample Usage</dt><dd><strong>1</strong> or <strong>{vSecond}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




<a id="param_7"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CreateDateTimeCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
