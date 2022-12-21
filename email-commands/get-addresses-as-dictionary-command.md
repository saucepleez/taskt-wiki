<!--TITLE: Get Addresses As Dictionary Command -->
<!-- SUBTITLE: a command in the EMail Commands group. -->
[Go To Automation Commands Overview](/automation-commands.md)


EMail Commands &gt; Get Addresses As Dictionary


# Get Addresses As Dictionary Command


## What does this command do?
This command allows you to get Addresses from EMail.


## When would I want to use this command?
Use this command when you want to get Addresses from EMail.


<a id="param_list"></a>
## Command Parameters
- [Please specify EMail Variable Name](#param_0)
- [Please specify Address Type](#param_1)
- [Please specify Variable Name to Store Addresses](#param_2)
- [Please Specify the Comment Field (Optional)](#param_3)


<a id="param_0"></a>
### Please specify EMail Variable Name


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Instance Type</dt><dd>MailKitEMail</dd>
<dt>Parameter Direction</dt><dd>Input</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>{vEMail}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_0) / [list](#param_list) / [next](#param_1)


</div>


<a id="param_1"></a>
### Please specify Address Type


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Selection Values (Case Sensitive: No, Whilte-Space Sensitive: Yes)</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>From</strong> or  <strong>To</strong> or  <strong>CC</strong> or  <strong>BCC</strong> or  <strong>Reply-To</strong> or  <strong>Resent-From</strong> or  <strong>Resent-To</strong> or  <strong>Resent-CC</strong> or  <strong>Resent-BCC</strong> or  <strong>Resent-Reply-To</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_1) / [list](#param_list) / [next](#param_2)


</div>


<a id="param_2"></a>
### Please specify Variable Name to Store Addresses


<dl>
<dt>What to input</dt><dd>(nothing)</dd>
<dt>Value</dt><dd>Variables</dd>
<dt>Parameter Direction</dt><dd>Output</dd>
<dt>Error Occurs When the Value is ...</dt><dd><ul>
<li>Empty</li>
</ul></dd>
<dt>Sample Usage</dt><dd><strong>vAddresses</strong> or <strong>{vAddresses}</strong></dd>
<dt>Remarks</dt><dd>(nothing)</dd>
</dl>




<div style="font-size: 90%; text-align: center">


[prev](#param_2) / [list](#param_list) / [next](#param_3)


</div>


<a id="param_3"></a>
### Please Specify the Comment Field (Optional)


<dl>
<dt>What to input</dt><dd>Optional field to enter a custom comment which could potentially describe this command or the need for this command, if required</dd>
<dt>Sample Usage</dt><dd>(nothing)</dd>
<dt>Remarks</dt><dd>Optional</dd>
</dl>




## Developer/Additional Reference
Automation Class Name: MailKitGetAddressesAsDictionaryCommand
Parent Namespace: taskt.Core.Automation.Commands
This page was generated on 12/21/22 09:51 PM


## Help
- [Open/Report an issue on GitHub](https://github.com/rcktrncn/taskt/issues/new)
- [Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
