<h1>Release Note:</h1>
<h2>Title: Protected Files Not Displayed in Detailed Migration Report for Specific Locales</h2>
<h2>Issue ID: [002472 - Internal tracking ID]</h2>
<h2>Product: Dell Migrate</h2>
<h2>Component: Detailed Migration Report</h2>
<h2>Affected Versions: Dell Migrate (All versions before 3.11)</h2>
<h2>Locales Affected: Spanish (Spain), French (Canada)</h2>

<hr style="border: 1px solid #ccc; margin: 20px 0;">

<h2>Issue Summary</h2>
<p>When running Dell Migrate, customers in the Spanish (Spain) and French (Canada) locales do not see Protected Files listed in the Skipped Files section of the Detailed Migration Report.

</p>
<hr style="border: 1px solid #ccc; margin: 20px 0;">

<h2>Expected Behavior</h2>
<p>Protected system files (e.g., .dll, .exe, .ocx, .sys) are not transferred during migration as they may cause compatibility issues on the new system.

Upon completion of the migration, all skipped Protected Files should be listed under the Skipped Files section in the Detailed Migration Report.</p>
<hr style="border: 1px solid #ccc; margin: 20px 0;">

<h2>Known Issue</h2>
<ul>
 <li>Protected system files (e.g., .dll, .exe, .ocx, .sys) are not transferred during migration as they may cause compatibility issues on the new system.</li>
<li>The Protected Files are still correctly skipped during the migration process—only their visibility in the report is affected.</li>
<h2>Resolution</h2>
<p>This issue has been identified and will be resolved in the upcoming 3.11 release of SupportAssist.</p>
<hr style="border: 1px solid #ccc; margin: 20px 0;">
  
<h2>Workaround</h2>
<ul>
  <li>As a temporary solution, users may change their locale settings to another supported language before initiating the migration process.</li>
  <li>This change will not alter the migration results but allow users to view all skipped files, including Protected Files, in the report.</li>
</ul>
<hr style="border: 1px solid #ccc; margin: 20px 0;">
<h2>Impact</h2>
<ul>This issue is limited to report visibility only. It does not affect the actual migration process or data integrity.</ul>
<ul>All Protected Files continue to be appropriately skipped.</ul>

