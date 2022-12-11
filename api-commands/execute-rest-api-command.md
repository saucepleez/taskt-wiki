<!--TITLE: Execute REST API Command -->
<!-- SUBTITLE: a command in the API Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


API Commands &gt; Execute REST API


# Execute REST API Command


## What does this command do?
This command allows you to show a message to the user.


## When would I want to use this command?
Use this command when you want to present or display a value on screen to the user.


## Command Parameters
- [Please enter the Base URL (ex. http://mysite.com)](#param_0)
- [Please enter the endpoint (Ex. /v2/endpoint)](#param_1)
- [Please select method type](#param_2)
- [Advanced REST Parameters](#param_3)
- [Basic REST Parameters](#param_4)
- [Apply Result To Variable](#param_5)
- [Please select method type](#param_6)
- [Comment Field (Optional)](#param_7)


<a id="param_0"></a>
### Please enter the Base URL (ex. http://mysite.com)


<dl>
<dt>What to input</dt><dd>Define any API endpoint which contains the full URL.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>https://example.com</strong> or <strong>{vMyUrl}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please enter the endpoint (Ex. /v2/endpoint)


<dl>
<dt>What to input</dt><dd>Define any API endpoint which contains the full URL.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>/v2/getUser/1</strong> or <strong>{vMyUrl}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please select method type


<dl>
<dt>What to input</dt><dd>Select the necessary method type.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>GET</strong> or  <strong>POST</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Advanced REST Parameters


<dl>
<dt>What to input</dt><dd>Specify a list of advanced parameters.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Basic REST Parameters


<dl>
<dt>What to input</dt><dd>Specify default search parameters</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>n/a</dd>
<dt>Remarks</dt><dd>Once you have clicked on a valid window the search parameters will be populated.  Enable only the ones required to be a match at runtime.</dd>
</dl>




<a id="param_5"></a>
### Apply Result To Variable


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_6"></a>
### Please select method type


<dl>
<dt>What to input</dt><dd>Select the necessary method type.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Json</strong> or  <strong>Xml</strong> or  <strong>None</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_7"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RESTCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
