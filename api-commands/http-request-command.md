<!--TITLE: HTTP Request Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)
API Commands &gt; HTTP Request


# HTTP Request Command


## What does this command do?
This command downloads the HTML source of a web page for parsing


## When would I want to use this command?
Use this command when you want to retrieve HTML of a web page without using browser automation.


## Command Parameters
- [Please Enter the URL](#param_0)
- [Execute Request as the currently logged on user?](#param_1)
- [Apply Result To Variable](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please Enter the URL


<dl>
<dt>What to input</dt><dd>Enter a valid URL that you want to collect data from.</dd>
<dt>Sample Data</dt><dd>http://mycompany.com/news or {vURL}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Execute Request as the currently logged on user?


<dl>
<dt>What to input</dt><dd>Sets currently logged on user authentication information for the request.</dd>
<dt>Sample Data</dt><dd>Select 'Yes' or 'No'</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Apply Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Data</dt><dd>vSomeVariable</dd>
<dt>Remarks</dt><dd>If you have enabled the setting Create Missing Variables at Runtime then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: HTTPRequestCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/10/22 01:48 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
