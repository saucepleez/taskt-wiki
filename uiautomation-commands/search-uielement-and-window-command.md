<!--TITLE: Search UIElement And Window Command -->
<!-- SUBTITLE: a command in the UIAutomation group. -->
[Go To Automation Commands Overview](/automation-commands.md)


UIAutomation &gt; Search UIElement & Window &gt; Search UIElement And Window


# Search UIElement And Window Command


## What does this command do?
This command allows you to get UIElement from Window Name.


## When would I want to use this command?



<a id="param_list"></a>
## Command Parameters
- [Please Select the Window Name](#param_0)
- [Please Specify the Search Parameters](#param_1)
- [Please Select the Variable Name to Store UIElement](#param_2)
- [Optional - Please Select the Check Method for the Window Name](#param_3)
- [Optional - Please Selection Method for the Window Name](#param_4)
- [Optional - Please Specify the Window Index](#param_5)
- [Optional - Please Specify the Wait Time for the Window to Exist (sec)](#param_6)
- [Optional - Please Specify the Wait Time for the UIElement to Exist (sec)](#param_7)
- [Optional - Please Select the Variable Name to Store Window Name Result](#param_8)
- [Optional - Please Select the Variable Name to Store Window Handle Result](#param_9)
- [Optional - Please Specify the Comment Field](#param_10)


<a id="param_0"></a>
### Please Select the Window Name


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Name</dd>
<dt>Value</dt><dd>Window Names</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Untitled - Notepad</strong> | Specify the **Notepad** |
| <strong>{Window.CurrentWindowName}</strong> | Specify the Current Activate Window |
| <strong>{vWindow}</strong> | Specify Value of Variable **vWindow** for Window Name |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Specify the Search Parameters


<dl>
<dt>What to input</dt><dd>Enter or Select the Search Paramters</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Select the Variable Name to Store UIElement


<dl>
<dt>What to input</dt><dd>Enter or Select the UIElement Variable Name</dd>
<dt>Value</dt><dd>UIElement Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the Check Method for the Window Name


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>Contains</strong> or  <strong>Starts with</strong> or  <strong>Ends with</strong> or  <strong>Exact match</strong> or  <strong>Not Contains</strong> or  <strong>Not Starts with</strong> or  <strong>Not Ends with</strong> or  <strong>Not Match</strong> or  <strong>Wildcard</strong> or  <strong>Not Wildcard</strong> or  <strong>Not Empty</strong> or  <strong>Is Number</strong> or  <strong>Is Boolean</strong> or  <strong>Is Boolean Loose</strong> or  <strong>Is Empty</strong> or  <strong>Is Not Number</strong> or  <strong>Is Not Boolean</strong> or  <strong>Is Not Boolean Loose</strong></dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>Contains</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>Contains</strong> | It's like Comparing whether to Contains **hello**. |
| <strong>Starts with</strong> | It's like Comparing whether to Starts With **hello**. |
| <strong>Ends with</strong> | It's like Comparing whether to Ends With **hello**. |
| <strong>Exact match</strong> | It's like Comparing whether an Exact match to **hello**. |
| <strong>Not Contains</strong> | It's like Comparing whether to Not Contains **hello**. |
| <strong>Not Starts with</strong> | It's like Comparing whether to Not Starts With **hello**. |
| <strong>Not Ends with</strong> | It's like Comparing whether to Not Ends With **hello**. |
| <strong>Not Match</strong> | It's like Comparing whether an Not Matche to **hello**. |
| <strong>Not Empty</strong> | This determines not empty text. |
| <strong>Wildcard</strong> | Check for Wildcard match. |
| <strong>Not Wildcard</strong> | Check for Wildcard Not match. |
| <strong>Is Number</strong> | This determines whether a number. |
| <strong>Is Boolean</strong> | This determines whether a boolean, such as **True** or **False**. |
| <strong>Is Boolean Loose</strong> | This determines whether it is a loose boolean, such as **True**, **False**, **Yes**, **No**, **1**, or **0**. |
| <strong>Is Empty</strong> | This determines empty text. |
| <strong>Is Not Number</strong> | This determines whether it is **Not** a number. |
| <strong>Is Not Boolean</strong> | This determines whether it is **Not** a boolean, such as **True** or **False**. |
| <strong>Is Not Boolean Loose</strong> | This determines whether it is **Not** a loose boolean, such as **True**, **False**, **Yes**, **No**, **1**, or **0**. |


<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Selection Method for the Window Name


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
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


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Optional - Please Specify the Window Index


<dl>
<dt>What to input</dt><dd>Enter or Select the Window Index</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>0 or 1 or {vIndex}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>0</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>0</strong> | Specify the First Window |
| <strong>1</strong> | Specify **1** for Window Index |
| <strong>{vIndex}</strong> | Specify Value of Variable **vIndex** for Window Index |


<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Wait Time for the Window to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the Window is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Optional - Please Specify the Wait Time for the UIElement to Exist (sec)


<dl>
<dt>What to input</dt><dd>Number Greater than or Equal 0</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Less than Zero</li>
</ul></dd>
<dt>Sample Usage</dt><dd>10 or {vWaitTime}</dd>
<dt>Remarks</dt><dd>Specify how long to Wait before an Error will occur because the UIElement is Not Found.<br><br>
<strong>Optional</strong><br>Default Value is <strong>10</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>10</strong> | Specify **10** for Wait Time |
| <strong>{vWaitTime}</strong> | Specify Value of Variable **vWaitTime** for Wait Time |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Select the Variable Name to Store Window Name Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vWin or {vWin}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vWin</strong> | Specify Variable Name **vWin** |
| <strong>{vWin}</strong> | Specify Variable Name **vWin** |


<div style="font-size: 90%; text-align: center">


[prev](#param_8) / [list](#param_list) / [next](#param_9)


</div>


<a id="param_9"></a>
### Optional - Please Select the Variable Name to Store Window Handle Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>WindowHandle Variable</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vHandle or {vHandle}</dd>
<dt>Remarks</dt><dd>When Match Method is <strong>All</strong>, data type is LIST, otherwise it is BASIC<br><br>
<strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vHandle</strong> | Specify Variable Name **vHandle** |
| <strong>{vHandle}</strong> | Specify Variable Name **vHandle** |


<div style="font-size: 90%; text-align: center">


[prev](#param_9) / [list](#param_list) / [next](#param_10)


</div>


<a id="param_10"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_10) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: UIAutomationSearchUIElementAndWindowCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 11/02/25 04:56 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
