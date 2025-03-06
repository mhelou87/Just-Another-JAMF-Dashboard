# Just Another Jamf Dashboard

A Google Sheets template for a custom Jamf dashboard - a tool to help your IT/MDM teams manage their environment and quickly share high-level views of what's under the hood with stakeholders.

While this was designed with the JAMF MDM product in mind, it could likely be adapted for other tools as well. 

### Tab Guide:
- Dashboard; This pulls data from the other tabs, providing the simplist high-level view.
- PreStage Enrollment; If you have multiple PSE, keep notes on what's being configured or enforced.
- Policies; List out what policies are executing, whether they are Scripts, PKG, or "Other" payloads in effect. Additional columns help indicate the use of custom PKG builds, the scoping at a PSE level, as well as keeping notes or reference links. 
- Configuration Profiles; Lists out what ConfigProfiles are being pushed down indicating simple scoping by PSE. 
- Extension Attributes; Lists out what ExtAttr are being used. 
- Maintenance; This pulls data from other tabs and provides a Monthly Calendar to let you schedule out any required maintenance needs. If you ever need to audit the assets in one of your PSE's, update a PKG from a vendor, or update a batch of Smart Groups, this can let you find an optimal scheduling cadence and provide links to the scheduled event for reference. 
