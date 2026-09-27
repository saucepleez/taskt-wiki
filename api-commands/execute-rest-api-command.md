<!--TITLE: Execute REST API Command -->
<!-- SUBTITLE: a command in the API group. -->
[Go To Automation Commands Overview](/automation-commands.md)


API &gt; Execute REST API


# Execute REST API Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the Base URL](#param_0)
- [Optional - Please Specify the Port](#param_1)
- [Please Specify the Endpoint](#param_2)
- [Please Select the Method Type](#param_3)
- [Please Specify the Basic REST Parameters](#param_4)
- [Please Select the Variable Name to Store Result](#param_5)
- [Please Specify the Advanced REST Parameters](#param_6)
- [Please Select the Format Type](#param_7)
- [Optional - Please Specify the Timeout (sec)](#param_8)
- [Optional - Please Specify the Comment Field](#param_9)


<a id="param_0"></a>
### Please Specify the Base URL


<dl>
<dt>What to input</dt><dd>Enter or Select the Bsae URL</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>https://example.com or 192.168.1.2 or {vURL}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>https://example.com</strong> | URL |
| <strong>192.168.1.2</strong> | URL |
| <strong>{vURL}</strong> | Specify Value of Variable **vURL** for URL |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Port


<dl>
<dt>What to input</dt><dd>Enter or Select the Port</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>8080 or {vPort}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>8080</strong> | URL |
| <strong>{vPort}</strong> | Specify Value of Variable **vPort** for URL |


<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Endpoint


<dl>
<dt>What to input</dt><dd>Enter or Select the Endpoint</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd>/v2/getUser/1 or {vMyURL}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>/v2/getUser/1</strong> | Specify **/v2/getUser/1** for Endpoint |
| <strong>{vMyURL}</strong> | Specify Value of Variable **vMyURL** for Endpoint |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Select the Method Type


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>GET</strong> or  <strong>POST</strong> or  <strong>PUT</strong> or  <strong>DELETE</strong> or  <strong>PATCH</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Specify the Basic REST Parameters


<dl>
<dt>What to input</dt><dd>Specify default search parameters</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Once you have clicked on a valid window the search parameters will be populated.  Enable only the ones required to be a match at runtime.</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Select the Variable Name to Store Result


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
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


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Please Specify the Advanced REST Parameters


<dl>
<dt>What to input</dt><dd>Specify a list of advanced parameters.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / [next](#param_7)


</div>


<a id="param_7"></a>
### Please Select the Format Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>JSON</strong> or  <strong>XML</strong> or  <strong>None</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| GeneralPropertyControls | v_ComboBox |


<div style="font-size: 90%; text-align: center">


[prev](#param_7) / [list](#param_list) / [next](#param_8)


</div>


<a id="param_8"></a>
### Optional - Please Specify the Timeout (sec)


<dl>
<dt>What to input</dt><dd>Enter or Select the Timeout</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>30 or {vTime}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>60</strong></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>30</strong> | Specify **30** for Timeout |
| <strong>{vTime}</strong> | Specify Value of Variable **vTime** for Timeout |


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
Automation Class Name: HTTPExecuteRESTAPICommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
