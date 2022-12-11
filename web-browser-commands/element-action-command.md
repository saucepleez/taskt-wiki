<!--TITLE: Element Action Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Actions &gt; Element Action


# Element Action Command


## What does this command do?
This command allows you to close a Selenium web browser session.


## When would I want to use this command?
Use this command when you want to manipulate, set, or get data on a webpage within the web browser.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Element Search Method](#param_1)
- [Element Search Parameter](#param_2)
- [Target Element Index (Only Use Fined Elements ***)](#param_3)
- [Element Action](#param_4)
- [Additional Parameters](#param_5)
- [Comment Field (Optional)](#param_6)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Browser</strong> command</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Element Search Method


<dl>
<dt>What to input</dt><dd>Select the specific search type that you want to use to isolate the element in the web page.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select <strong>Find Element By XPath</strong>, <strong>Find Element By ID</strong>, <strong>Find Element By Name</strong>, <strong>Find Element By Tag Name</strong>, <strong>Find Element By Class Name</strong>, <strong>Find Element By CSS Selector</strong>, <strong>Find Element By Link Text</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Element Search Parameter


<dl>
<dt>What to input</dt><dd>Specifies the parameter text that matches to the element based on the previously selected search type.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>If search type <strong>Find Element By ID</strong> was specified, for example, given <div id='name'></div>, the value of this field would be <strong>name</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Target Element Index (Only Use Fined Elements ***)


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>0</strong> or <strong>1</strong> or <strong>{vIndex}</strong></dd>
<dt>Remarks</dt><dd>If parameter is $x('//div') and index is 5, it's means target is $x('//div')[5].</dd>
</dl>




<a id="param_4"></a>
### Element Action


<dl>
<dt>What to input</dt><dd>Select the appropriate corresponding action to take once the element has been located</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select from <strong>Invoke Click</strong>, <strong>Left Click</strong>, <strong>Right Click</strong>, <strong>Middle Click</strong>, <strong>Double Left Click</strong>, <strong>Clear Element</strong>, <strong>Set Text</strong>, <strong>Get Text</strong>, <strong>Get Attribute</strong>, <strong>Wait For Element To Exist</strong>, <strong>Get Count</strong></dd>
<dt>Remarks</dt><dd>Selecting this field changes the parameters that will be required in the next step</dd>
</dl>




<a id="param_5"></a>
### Additional Parameters


<dl>
<dt>What to input</dt><dd>Additioal Parameters will be required based on the action settings selected.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>Additional Parameters range from adding offset coordinates to specifying a variable to apply element text to.</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_6"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserElementActionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
