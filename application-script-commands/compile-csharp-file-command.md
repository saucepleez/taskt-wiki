<!--TITLE: Compile CSharp File Command -->
<!-- SUBTITLE: a command in the Application/Script group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Application/Script &gt; Windows Script File &gt; Compile CSharp File


# Compile CSharp File Command


## What does this command do?
This command allows you to compile C# file (*.cs) from the input


## When would I want to use this command?
Use this command when you want to compile custom C# file (*.cs) commands.  The code in this command is compiled and run at runtime when this command is invoked.  This command only supports the standard framework classes.


<a id="param_list"></a>
## Command Parameters
- [Please Specify the C# File Path](#param_0)
- [Optional - Please Specify the Compiled Executable File Name](#param_1)
- [Optional - Please Select the Variable Name to Store Executable File Path](#param_2)
- [Optional - Please Select the C# Language Version](#param_3)
- [Optional - Please Specify the Comment Field](#param_4)


<a id="param_0"></a>
### Please Specify the C# File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the C# File</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>File Path Setting</dt><dd><ul><li>Allow URL: Yes</li><li>File Extension and Existance: Extension Required, Existance Required</li><li>Support Extensions: cs</li><li>FileCounter Variable Support: No Support</li></ul></dd>
<dt>Sample Usage</dt><dd>C:\temp\mycode.cs or {vSourcePath}</dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>C:\temp\mycode.cs</strong> | Specify **C:\temp\mycode.cs** for C# File |
| <strong>{vSourcePath}</strong> | Specify Value of Variable **vSourcePath** for C# File |


<div style="font-size: 90%; text-align: center">


prev / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Optional - Please Specify the Compiled Executable File Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br>Default Value is <strong>tasktOnTheFly</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Optional - Please Select the Variable Name to Store Executable File Path


<dl>
<dt>What to input</dt><dd>Enter or Select the Variable Name</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>The Parameter for Storing the Result of command execution</dd>
<dt>Sample Usage</dt><dd>vResult or {vResult}</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




#### More Detailed Sample Usage(s)
| Value | Means |
|---|---|
| <strong>vResult</strong> | Specify Variable Name **vResult** |
| <strong>{vResult}</strong> | Specify Variable Name **vResult** |


<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Optional - Please Select the C# Language Version


<dl>
<dt>What to input</dt><dd>Select or Enter the One of the Options</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Parameter Direction</dt><dd>The Input Parameter for Executing the command</dd>
<dt>Sample Usage</dt><dd><strong>default</strong> or  <strong>latest</strong> or  <strong>preview</strong> or  <strong>14.0</strong> or  <strong>13.0</strong> or  <strong>12.0</strong> or  <strong>11.0</strong> or  <strong>10.0</strong> or  <strong>9.0</strong> or  <strong>8.0</strong> or  <strong>7.3</strong> or  <strong>7.2</strong> or  <strong>7.1</strong> or  <strong>7</strong> or  <strong>6</strong> or  <strong>5</strong> or  <strong>4</strong> or  <strong>3</strong> or  <strong>2</strong> or  <strong>1</strong></dd>
<dt>Remarks</dt><dd>More Information: https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/configure-language-version?WT.mc_id=AI-MVP-123445<br><br>
<strong>Optional</strong><br>Default Value is <strong>default</strong></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_3) / [list](#param_list) / [next](#param_4)


</div>


<a id="param_4"></a>
### Optional - Please Specify the Comment Field


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_4) / [list](#param_list) / next


</div>


## Developer/Additional Reference
Automation Class Name: CompileCSharpFileCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 09/27/26 12:03 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
