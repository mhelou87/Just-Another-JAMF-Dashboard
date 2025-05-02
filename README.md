# Just Another JAMF Dashboard

A Google Sheets template for a JAMF dashboard - a tool to help your IT/MDM/CPE teams manage their environment and share high-level views with stakeholders.

While this was designed with the JAMF product in mind, it could be adapted for other tools as well. This is meant to be a starting point, feel free to make further customizations as needed by your environment.

## Tab Guide:
**Dashboard** <br> This pulls data from the other tabs, providing the simplest high-level view of the JSS. Users will need to update all formulae on this tab after duplicating the Google Sheet. 

**PreStage Enrollment**; <br> Keep notes on what's being configured or enforced by payload, identify distinct groups.

**Policies**; <br> See how Policies are configured, like if they are using scripts or PKGs & the availability via Policy or Self Service. Additional columns help indicate the use of JAMF Composer for custom PKG builds, the scoping at PreStage Enrollment level.

**Configuration Profiles**; <br> Lists out what is being pushed down, indicating simple scoping by PreStage Enrollment. 

**Extension Attributes**; <br> Lists out what ExtAttr are being used. 

**Maintenance**; <br> This pulls data from other tabs and provides a 12 month calendar to let you schedule out any required maintenance needs. Wether that's auditing the assets in a PreStage Enrollment, updating a PKG from a vendor, or updating Smart Group parameters, this can let you find an optimal scheduling cadence and you can utilize Google Sheet's "Smart Chips" to provide a link to the event for reference. 
