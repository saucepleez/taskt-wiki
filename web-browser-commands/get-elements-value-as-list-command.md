<!--TITLE: Get Elements Value As List Command -->
<!-- SUBTITLE: a command in the Web Browser Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
Web Browser Commands &gt; Scraping &gt; Get Elements Value As List


# Get Elements Value As List Command


## What does this command do?
This command allows you to get a Attribute value for Elements As List.


## When would I want to use this command?
Use this command when you want to get a Attribute value for Elements As List.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Please Specify Element Search Method](#param_1)
- [Please Specify Element Search Parameter](#param_2)
- [Please Specify Attribute Name to Get](#param_3)
- [Please Specify List Variable Name to store result](#param_4)
- [Comment Field (Optional)](#param_5)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the Create Browser command</dd>
<dt>Sample Data</dt><dd>myInstance or {vInstance}</dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call Create Browser command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Please Specify Element Search Method


<dl>
<dt>What to input</dt><dd>Select the specific search type that you want to use to isolate the element in the web page.</dd>
<dt>Sample Data</dt><dd>Select Find Element By XPath, Find Element By ID, Find Element By Name, Find Element By Tag Name, Find Element By Class Name, Find Element By CSS Selector, Find Element By Link Text</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Specify Element Search Parameter


<dl>
<dt>What to input</dt><dd>Specifies the parameter text that matches to the element based on the previously selected search type.</dd>
<dt>Sample Data</dt><dd>If search type Find Element By ID was specified, for example, given <div id='name'></div>, the value of this field would be name</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify Attribute Name to Get


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>id or Text or textContent or {vAttribute}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Please Specify List Variable Name to store result


<dl>
<dt>What to input</dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
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
Automation Class Name: SeleniumBrowserGetElementsValueAsListCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
