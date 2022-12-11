<!--TITLE: Get Elements Value As Dictionary Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Web Browser Commands &gt; Scraping &gt; Get Elements Value As Dictionary


# Get Elements Value As Dictionary Command


## What does this command do?
This command allows you to get a Attribute value for Elements As Dictionary.


## When would I want to use this command?
Use this command when you want to get a Attribute value for Elements As Dictionary.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Specify Element Search Method](#param_1)
- [Please Specify Element Search Parameter](#param_2)
- [Please specify Attribute Name to Get](#param_3)
- [Please Specify Dictionary Variable Name to store result](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Browser</strong> command</dd>
<dt>Instance Type</dt><dd>WebBrowser</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>{vInstance}</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Browser</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Specify Element Search Method


<dl>
<dt>What to input</dt><dd>Select the specific search type that you want to use to isolate the element in the web page.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>Select <strong>Find Element By XPath</strong>, <strong>Find Element By ID</strong>, <strong>Find Element By Name</strong>, <strong>Find Element By Tag Name</strong>, <strong>Find Element By Class Name</strong>, <strong>Find Element By CSS Selector</strong>, <strong>Find Element By Link Text</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify Element Search Parameter


<dl>
<dt>What to input</dt><dd>Specifies the parameter text that matches to the element based on the previously selected search type.</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>If search type <strong>Find Element By ID</strong> was specified, for example, given <div id='name'></div>, the value of this field would be <strong>name</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please specify Attribute Name to Get


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>id</strong> or <strong>Text</strong> or <strong>textContent</strong> or <strong>{vAttribute}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please Specify Dictionary Variable Name to store result


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_5"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: SeleniumBrowserGetElementsValueAsDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:24 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
