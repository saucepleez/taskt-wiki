<!--TITLE: Define Database Connection Command -->
<!-- SUBTITLE: a command in the Database Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Database Commands &gt; Define Database Connection


# Define Database Connection Command


## What does this command do?
This command allows you to define a connection to an OLEDB data source


## When would I want to use this command?
Use this command to create a new connection to a database.


## Command Parameters
- [Please Enter the instance name](#param_0)
- [Define Connection String](#param_1)
- [Define Connection String Password](#param_2)
- [Test Connection Before Proceeding](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Enter the instance name


<dl>
<dt>What to input</dt><dd>Enter the unique instance name that was specified in the <strong>Create Excel</strong> command</dd>
<dt>Instance Type</dt><dd>DataBase</dd>
<dt>Parameter Direction</dt><dd>Output</dd><dt>Sample Data</dt><dd><strong>myInstance</strong> or <strong>seleniumInstance</strong></dd>
<dt>Remarks</dt><dd>Failure to enter the correct instance name or failure to first call <strong>Create Excel</strong> command will cause an error</dd>
</dl>




<a id="param_1"></a>
### Define Connection String


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Define Connection String Password


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Test Connection Before Proceeding


<dl>
<dt>What to input</dt><dd>Select an option which best fits to the specification you would like to make.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd>Select one of the provided options.</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_4"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: DatabaseDefineConnectionCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
