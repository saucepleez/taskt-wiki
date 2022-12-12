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
- [Please Specify the Enter the path to the powershell script (ex. C:\temp\myscript.ps, {vScriptPath})](#param_0)
- [Please Specify the Enter Powershell Command Arguments](#param_1)
- [Please Select the Convert variables before execution](#param_2)
- [Please Specify the Optional - Select the variable to receive the output](#param_3)
- [Please Specify the Comment Field (Optional)](#param_4)


<a id="param_0"></a>
### Please Specify the Enter the path to the powershell script (ex. C:\temp\myscript.ps, {vScriptPath})


<dl>
<dt>What to input</dt><dd>Enter a fully qualified path to the script, including the script extension.</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>This command differs from <strong>Start Process</strong> because this command blocks execution until the script has completed. If you do not want to stop while the script executes, consider using <strong>Start Process</strong> instead.
If file does not contain extensin, supplement ps1 or bat extension.
If file does not contain folder path, file will be opened in the same folder as script file.</dd>
</dl>




<a id="param_1"></a>
### Please Specify the Enter Powershell Command Arguments


<dl>
<dt>What to input</dt><dd>Enter any necessary arguments</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Please Select the Convert variables before execution


<dl>
<dt>What to input</dt><dd>Select the necessary option.</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Sample Usage</dt><dd><strong>Yes</strong> or  <strong>No</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_3"></a>
### Please Specify the Optional - Select the variable to receive the output


<dl>
<dt>What to input</dt><dd>Select or provide a variable from the variable list</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>If you have enabled the setting <strong>Create Missing Variables at Runtime</strong> then you are not required to pre-define your variables, however, it is highly recommended.</dd>
</dl>




<a id="param_4"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: RunPowershellCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/12/22 09:29 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
