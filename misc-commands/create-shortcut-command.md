<!--TITLE: Create Shortcut Command -->
<!-- SUBTITLE: a command in the Misc Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


Misc Commands &gt; Other &gt; Create Shortcut


# Create Shortcut Command


## What does this command do?
This command allow to create shortcut file


## When would I want to use this command?
Use this command when you want to create shortcut file


## Command Parameters
- [Please specify Shortcut Target File, Folder, or URL](#param_0)
- [Please specify saved Shortcut Path](#param_1)
- [Optional - Please specify Shortcut Description](#param_2)
- [Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify Shortcut Target File, Folder, or URL


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\target.txt</strong> or <strong>C:\temp</strong> or <strong>http://example.com</strong> or <strong>{vPath}}</strong> or <strong>{vURL}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_1"></a>
### Please specify saved Shortcut Path


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Error When Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd><dt>Sample Data</dt><dd><strong>C:\temp\shortcut.lnk</strong> or <strong>C:\temp\shortcut.url</strong> or <strong>{vShortcut}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<a id="param_2"></a>
### Optional - Please specify Shortcut Description


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd><strong>Optional</strong><br></dd>
</dl>




<a id="param_3"></a>
### Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt></dt><dd></dd>
<dt>Sample Data</dt><dd>I am using this command to ...</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: CreateShortcutCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/11/22 06:22 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
