*Actionpack for Workflow Log Parsing*
=============


Actionpack for modifying Automic Objects and Retrieving, Processing and Extracting content from Action Reports / Outputs
http://github.com/Automic-Community/Actionpack-for-Workflow-Log-Parsing

<!-- List of attached files -->
Contents of Solution Package:

						
								*PCK.CUSTOM_AUTOMIC_OBJECTS_1.0.2.zip
								
						


Documenation and Instructions
---

<p>This action pack should make it easier to implement scenarios requiring to pass values that are generated at runtime and appear in an action output.</p>
<p>ex:&nbsp;</p>
<ol>
<li>Action runs and returns an ID number in its REP (output)</li>
<li>ID Number is stored in an Automic Variable and passed</li>
<li>the ID Number is then used in another action downstream</li>
</ol>
<p>This process typically implies fiddling with the PREP_PROCESS instructions in the PostProcess tab.. This action pack is built to NOT have to do that anymore.</p>
<p>Requirements:</p>
<p>In Client 0, add the following entry to your UC_SYSTEM_SETTINGS file:</p>
<p><strong>GENERATE_UNDEFINED_SCRIPT_VARS&nbsp; &nbsp; &nbsp;Y</strong></p>
<p>&nbsp;</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (https://marketplace.automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (https://marketplace.automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic-Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).