<h1>Known Issue: Protected Files Folders Are Not Showing in Detailed Migration Report for Specific Locales.
</h1>
<h2>Expected Behavior:</h2>
<p>When running Dell Migrate, Protected Files are not transferred.
Protected Files are system files that should not be transferred or manipulated. They typically have extensions such as .dll, .exe, .ocx, and .sys. It is generally appropriate to skip these files as they may cause compatibility issues on your new PC.
Once the migration is complete, customers will see these skipped Protected Files in the Detailed Migration Report in the Skipped Files list.
</p>
<h2>Known Issue:</h2>
<p>Customers running Dell Migrate from two specific locales, Spanish-Spain and French-Canada, will not see these Protected Files in the Skipped Files list.</p>
<h2>Resolution:</h2>
<p>This is a known issue that will be fixed in the 3.11 release of SupportAssist.
As a manual workaround, customers may consider changing their locale to another supported locale before running a migration. Since Dell Migrate skips Protected Files, there will be no change in the migration results. However, customers may use this workaround to be informed which files were skipped.</p>
