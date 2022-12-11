<!--TITLE: Run Powershell Command -->
<!-- SUBTITLE: a command in the Programs/Process Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Programs/Process Commands &gt; Run Powershell


# Run Powershell Command


## What does this command do?
This command allows you to run a powershell script and wait for it to exit before proceeding.


## When would I want to use this command?
Use this command when you want to run a powershell script and wait for it to close before taskt continues executing.


## Command Parameters
- [Enter the path to the powershell script (ex. C:\temp\myscript.ps, {vScriptPath})](#param_0)
- [Enter Powershell Command Arguments](#param_1)
- [Convert variables before execution](#param_2)
- [Optional - Select the variable to receive the output](#param_3)
- [Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Enter the path to the powershell script (ex. C:\temp\myscript.ps, {vScriptPath})


<dl>
<dt>What to input</dt><dd>Enter a fully qualified path to the script, including the script extension.</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>C:\temp\myscript.ps1</strong> or <strong>{vScriptPath}</strong></dd>
<dt>Remarks</dt><dd>This command differs from <strong>Start Process</strong> because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using <strong>Start Process</strong> instead.
If file does not contain extensin, supplement ps1 or bat extension.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_1"></a>
### Enter Powershell Command Arguments


<dl>
<dt>What to input</dt><dd>Enter any necessary arguments</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Convert variables before execution


<dl>
<dt>What to input</dt><dd>Select the necessary option.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Data</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Optional - Select the variable to receive the output


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd><strong>vSomeVariable</strong></dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
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
Automation Class Name: RunPowershellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
