# srm-equallogic
<H2>DIY Custom EqualLogic Reporting for EMC ViPR SRM</H2>

<p><b>Thanks to an internal lab I was able to get access to an EqualLogic PS6000 series array and an ESX server to deploy an SRM server and created a sample report of real EqualLogic data that I could use to validate that the report met my customers needs.  I also documented the process for installing this customized collector (SNMP Masks, Polling Group, and Reports) which I'm sharing here for others to use.</b></p>

<p><b>Install:</b><br />Please follow the instructions contained in the PDF file</p>

<p><b>Prerequisites:</b>
<li>EMC ViPR SRM Installed</li>
<li>Dell EqualLogic PS Series Storage Array Installed</li>
<li>Access to the Dell EqualLogic SNMP MIBs from Dell Support</li>
</p>
<p><b>What is included:</b><br />
Provided here are SNMP Masks and Translations files to use with SRM to get you started.  These work in conjunction with the SNMP MIBs provided by Dell to collect data from the EqualLogic systems.  Also included is a basic set of reports to import into EMC ViPR SRM.  Combined, these files will get you capacity and performance data in SRM for your EqualLogic systems.  
</p><p>
Once set up, you can edit the Masks to add additional collection data and you can modify the reports to add or manipulate the data to your needs.
</p>
