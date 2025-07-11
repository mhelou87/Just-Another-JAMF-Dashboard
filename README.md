# Just Another JAMF Dashboard
### Presented at MacAdmins 2025

<br>

![Screenshot of the Dashboard.](/images/dashboard-screenshot.png)

<br>

A Google Sheets template for a JAMF dashboard - a tool to help your IT/MDM/CPE teams manage their environment and share high-level views with stakeholders.

While this was designed with the JAMF product in mind, it could be adapted for other platforms as well. This is meant to be a starting point, feel free to make further customizations as needed.

Click [RIGHT HERE](https://docs.google.com/spreadsheets/d/1CpdAGVssBiA5Ef8Y49X9duA_e1Tlcjp7S0KEKbdiNcA/template/preview) to get a copy of this template.

<br>

## Getting Started

1. Click the link above to get your own copy of the template. Copy the new URL of your Sheet, "https..../edit", for the next step.
2. There are 6 formulas to update across two tabs; Dashboard and Maintenance.
    - Remove the placeholder *__$NEW_URL_HERE__* and insert your new URL within the quotes
    - Remove the leading *__!__* so the formula will activate
3. Review and make any customizations as desired. 
4. Fill in your data on the PreStage, Policies, Configuration Profiles, Extension Attributes, and Maintenance tabs. 

<br>

## Tab Guide:
**Dashboard** <br> This pulls data from the other tabs, providing the simplest high-level view of the JSS. Users will need to update the 4 formulas on this tab. 

**PreStage Enrollment** <br> Keep notes on what's being configured or enforced by payload.

**Policies** <br> List out Policies and see some configuration details, like if they are using scripts or PKGs & the availability via Policy or Self Service. Additional columns help indicate the use of JAMF Composer for custom PKG builds and availability to PreStage Enrollments.

**Configuration Profiles** <br> List out what is being pushed, indicating simple scoping by PreStage Enrollment. 

**Extension Attributes** <br> List out the state of ExtAttr's.

**Maintenance** <br> This pulls data from other tabs and provides a 12 month calendar to help you schedule out any required maintenance needs. Whether that's auditing the assets in a PreStage Enrollment, updating a PKG from a vendor, or updating Smart Group parameters, this can help you find an optimal scheduling cadence. Utilize Google Sheet's "Smart Chips" to provide a link to the calendar event for reference. Users will need to update the 2 formulas on this tab.

<br>
