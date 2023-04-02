<!--TITLE: Element Action Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Element Action


# Element Action Command


## What does this command do?
This command allows you to close a Selenium web browser session.


## When would I want to use this command?
Use this command when you want to manipulate, set, or get data on a webpage within the web browser.


<a id="param_list"></a>
## Command Parameters
- [Please Select the WebBrowser Instance Name](#param_0)
- [Please Select the Element Search Method](#param_1)
- [Please Specify the Element Search Parameter](#param_2)
- [Please Specify the Target Element Index (Only Use Fined Elements ***)](#param_3)
- [Please Select the Element Action](#param_4)
- [Please Specify the Additional Parameters](#param_5)
- [Optional - Please Specify the Comment Field](#param_6)


<a id="param_0"></a>
### Please Select the WebBrowser Instance Name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Browser</strong> command</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Sample Usage</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please Select the Element Search Method


<dl>
<dt>What to input</dt><dd>Select the specific search type that you want to use to isolate the element in the web page.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Find Element By XPath</strong> or  <strong>Find Element By ID</strong> or  <strong>Find Element By Name</strong> or  <strong>Find Element By Tag Name</strong> or  <strong>Find Element By Class Name</strong> or  <strong>Find Element By CSS Selector</strong> or  <strong>Find Element By Link Text</strong> or  <strong>Find Elements By XPath</strong> or  <strong>Find Elements By ID</strong> or  <strong>Find Elements By Name</strong> or  <strong>Find Elements By Tag Name</strong> or  <strong>Find Elements By Class Name</strong> or  <strong>Find Elements By CSS Selector</strong> or  <strong>Find Elements By Link Text</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please Specify the Element Search Parameter


<dl>
<dt>What to input</dt><dd>Specifies the parameter text that matches to the element based on the previously selected search type.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Target Element Index (Only Use Fined Elements ***)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If parameter is $x('//div') and index is 5, it's means target is $x('//div')[5].</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Please Select the Element Action


<dl>
<dt>What to input</dt><dd>Select the appropriate corresponding action to take once the element has been located</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Invoke Click</strong> or  <strong>Left Click</strong> or  <strong>Right Click</strong> or  <strong>Middle Click</strong> or  <strong>Double Left Click</strong> or  <strong>Clear Element</strong> or  <strong>Set Text</strong> or  <strong>Get Text</strong> or  <strong>Get Attribute</strong> or  <strong>Get Matching Elements</strong> or  <strong>Wait For Element To Exist</strong> or  <strong>Switch to frame</strong> or  <strong>Get Count</strong> or  <strong>Get Options</strong> or  <strong>Select Option</strong></dd>
<dt>Remarks</dt><dd>Selecting this field changes the parameters that will be required in the next step</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / [next](#param_5)


</div>


<a id="param_5"></a>
### Please Specify the Additional Parameters


<dl>
<dt>What to input</dt><dd>Additioal Parameters will be required based on the action settings selected.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_5) / [list](#param_list) / [next](#param_6)


</div>


<a id="param_6"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_6) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: SeleniumBrowserElementActionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 04/02/23 03:36 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
