<!--TITLE: UIElement Action Command -->
<!-- SUBTITLE: a command in the UIAutomation Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation Commands &gt; UIElement Action &gt; UIElement Action


# UIElement Action Command


## What does this command do?
Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the Window Name](#param_0)
- [Please Select the UIElement Action](#param_1)
- [Please Specify the Search Parameters](#param_2)
- [Please Specify the Action Parameters](#param_3)
- [Optional - Please Select the Search Method for the Window Name](#param_4)
- [Optional - Please Select the Match Method for the Window Name](#param_5)
- [Optional - Please Specify the Window Index](#param_6)
- [Optional - Please Specify the Wait Time for the Window to Exist (sec)](#param_7)
- [Optional - Please Specify the Wait Time for the UIElement to Exist (sec)](#param_8)
- [Optional - Please Specify the Comment Field](#param_9)


<a id="param_0"></a>
### Please Select the Window Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Name</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>Untitled - Notepad</strong> or <strong>Current Window</strong> or <strong>{vWindow}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Untitled - Notepad</strong> | Specify the **Notepad** |
| <strong>Current Window</strong> | Specify the Current Activate Window |
| <strong>{vWindow}</strong> | Specify Value of Variable **vWindow** for Window Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the UIElement Action


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Click UIElement</strong> or  <strong>Expand Collapse Items In UIElement</strong> or  <strong>Scroll UIElement</strong> or  <strong>Select UIElement</strong> or  <strong>Select Item In UIElement</strong> or  <strong>Set Text To UIElement</strong> or  <strong>Get Property Value From UIElement</strong> or  <strong>Check UIElement Exists</strong> or  <strong>Get Text From UIElement</strong> or  <strong>Get Selected State From UIElement</strong> or  <strong>Get Text From Table UIElement</strong> or  <strong>Wait For UIElement To Exists</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Search Parameters


<dl>
<dt>What to input</dt><dd>Enter or Select the Search Paramters</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Action Parameters


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Select the Search Method for the Window Name


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Contains</strong> or  <strong>Starts with</strong> or  <strong>Ends with</strong> or  <strong>Exact match</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Select the Match Method for the Window Name


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>First</strong> or  <strong>Last</strong> or  <strong>Index</strong></dd>
<dt>Remarks</dt><dd>Specify when there are Multiple Matching Windows<br><br>
<strong>Optional</strong><br>Default Value is <strong>First</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>First</strong> | Specify the First Window |
| <strong>Last</strong> | Specify the Last Window |
| <strong>Index</strong> | the Window specifed by Index. **0** means First Window |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Window Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Index</dd>
<dt>Sample Usage</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify the First Window |
| <strong>1</strong> | Specify **1** for Window Index |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Window Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Wait Time for the Window to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Sample Usage</dt><dd><strong>60</strong> or <strong>{vTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Window is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>60</strong> | Specify **60** for Wait Time |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Wait Time for the UIElement to Exist (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Wait Time</dd>
<dt>Sample Usage</dt><dd><strong>10</strong> or <strong>{vTime}</strong></dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the UIElement is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: UIAutomationUIElementActionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 08/20/23 05:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
