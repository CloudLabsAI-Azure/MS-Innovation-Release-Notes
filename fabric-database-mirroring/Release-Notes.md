# Fabric Database Mirroring

Welcome to the **Fabric Database Mirroring** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-06-30</summary>

## Release Date: 2026-06-30

### Summary of Changes

Enhanced the Microsoft Fabric Mirroring hands‑on labs documentation across the repository: added business "Scenario" sections, corrected and standardized step numbering, clarified procedural instructions (SAMI, connections, query editors, semantic models, and reporting), refreshed and added screenshots to reflect current UI, and improved the Getting Started guidance (VM zoom/resize). These are documentation-only updates aimed at improving learner clarity and reducing confusion during lab execution.

### Infrastructure Changes

NA

### Content Changes

- Getting Started
  - Reworked the getting-started page to include an explicit "Lab Scenario" section and clearer "Lab Overview" headings.
  - Added step-by-step guidance for VM view resizing and zoom controls (slider and zoom icon).
  - Replaced an environment screenshot with an updated image reflecting the current lab UI.

- Lab 01 (Azure SQL Database)
  - Added a "Scenario" section describing a business use case for mirroring Azure SQL Database into Fabric.
  - Fixed inconsistent step numbering (several numbered "1." entries corrected to sequential steps).
  - Clarified SAMI activation verification, Query Editor usage, and SSMS connection steps.
  - Replaced an outdated Query Editor screenshot and updated image references.

- Lab 02 (Azure Cosmos DB)
  - Added a "Scenario" section describing a Cosmos DB mirroring use case.
  - Clarified "Create new" vs "Use existing" container flow and corrected numbering.
  - Clarified visual query and view save flows; added guidance for semantic model creation and Power BI report steps.
  - Replaced several screenshots to match the current UI and notebook/visual query flows.

- Lab 03 (Azure SQL Managed Instance)
  - Added a "Scenario" section for mirroring from SQL Managed Instance.
  - Renumbered and reworded SSMS / table creation / sample data insertion steps for consistency.
  - Updated query monitoring screenshots and clarified where to check replication/ingestion status.

- Lab 04 (Snowflake)
  - Added a "Scenario" section explaining Snowflake → Fabric mirroring and Iceberg/Lakehouse integration.
  - Clarified OneLake delegated settings, creating OneLake shortcuts, and verifying metadata locations.
  - Updated step wording and image references for the OneLake and Lakehouse workflows.

- Lab 05 (Open Mirrored DBs / Landing Zone)
  - Added a "Scenario" section for ingesting change data into Fabric from a landing zone.
  - Improved step sequencing for creating an open mirrored DB and monitoring ingest/replication.

- Lab 06 (PostgreSQL)
  - Retitled header to "Lab 06" and added a "Scenario" section for Azure Database for PostgreSQL mirroring.
  - Clarified SAMI enablement, PGAdmin connection/query steps, and semantic model/report-building steps.
  - Updated screenshots for report creation and formatting guidance.

### Screenshot Updates

Updated screenshots to reflect current Azure / Microsoft Fabric UI and to improve clarity of step instructions.

- instructions/media/GSenvnew.png
  - New environment overview image used on the Getting Started page (replaces prior environment screenshot).

- instructions/media/Lab-01/L1T1S11new.png
  - Replaced Query Editor screenshot in Lab-01 to match current UI and show SAMI verification output.

- instructions/media/Lab-02/3015new.png
  - Replaced Cosmos DB Keys screenshot to show the current key reveal UI.

- instructions/media/Lab-02/new1.png
  - Replaced notebook/Lakehouse binding screenshot for improved visibility of binding steps.

- instructions/media/Lab-02/nsm.png
  - New semantic model pane screenshot used in Lab-02 to show model creation/selection.

- instructions/media/Lab-03/nsq.png
  - Updated SQL query toolbar screenshot used in Lab-03 for the ingestion/replication check step.

- instructions/media/Labresize.png
  - New Getting Started image showing the VM/Lab Guide pane slider and the three-vertical-dots UI element.

- instructions/media/Labzoom.png
  - New Getting Started image showing the A↕ zoom control and where to adjust lab guide zoom.

- instructions/media/No.png
  - Small UI screenshot used in the Getting Started page showing the "Stay signed in?" choice (used as part of the sign-in guidance).

      
### Testing Notes

- **Testing Date**: 2026-06-30

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>
<details>
  <summary>2026-04-20</summary>

## Release Date: 2026-04-20

### Summary of Changes

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues and enhanced the instructions wherever needed.

### Infrastructure Changes

Updated the scripts to validate the installtion of the tools required for the labs.

### Content Changes

N/A

### Screenshot Updates

Updated Fabric UI screenshots to reflect the latest UI.
      
### Testing Notes

- **Testing Date**: 2026-04-20

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>
<details>
  <summary>2026-04-04</summary>

## Release Date: 2026-04-04

### Summary of Changes

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues and enhanced the instructions wherever needed.

### Infrastructure Changes

NA

### Content Changes

N/A

### Screenshot Updates

In all the lab tasks updated with Fabric UI screenshots to reflect the latest UI and improve clarity.
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>
<details>
  <summary>2026-03-06</summary>

## Release Date: 2026-03-06

### Summary of Changes

Resolved deployment and configuration issues impacting Fabric mirroring of SQL Managed Instance and PostgreSQL in Lab 3 and Lab 6, respectively. Minor updates were also made by adding clearer, up-to-date UI screenshots.

### Infrastructure Changes

- Lab 3 Task 2 issue fix: 
  - Updated the API version used for the deployment of the SQL MI instance. The previous API version caused failures while retrieving DMV information during the Fabric mirroring. Updating the API version fixed the issue. 

- Lab 6 Task 1 issue fix:
  - Enabling the Fabric mirroring for PostgreSQL was failing. PostgreSQL was deployed on the Burstible SKU Tier, which is no longer supported for Fabric mirroring. Hence, we updated the template to deploy PostgreSQL with the General Purpose tier, which resolved the issue. 

### Content Changes

N/A

### Screenshot Updates

Updated few of the screenshots to reflect the latest UI and improve clarity.
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>

<details>
  <summary>2026-01-24</summary>

## Release Date: 2026-01-24

### Summary of Changes

Made minor updates by adding clearer, up-to-date UI screenshots.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

N/A
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end architecture validation and verification of prerequisites.

---
</details>

<details>
  <summary>2025-12-26</summary>

## Release Date: 2025-12-26

### Summary of Changes

Made minor updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity, improve accuracy, and ensure a smoother learning experience.  

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced screenshots to match the latest user interface.
      
### Testing Notes

- **Testing Date**: 2025-12-26

### Testing Scope 

Performed end-to-end architecture validation, including RBAC and policy compliance checks, and verification of prerequisites.

---
</details>

<details>
  <summary>2025-10-08</summary>

<details>
  <summary>2025-08-26</summary>

## Release Date: 2025-08-26

### Summary of Changes

Updated the ARM template, screenshots, and instructions.  

### Infrastructure Changes

- Updated the API Versions of the resources in the ARM template, as all of them were older versions.
- Updated the Custom Policy

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced the screenshots with clearer ones and enhanced the instructions. 
      
### Testing Notes

- **Testing Date**: 2025-08-25
- **Issue:** In Lab 4 Task 3, after connecting to the Snowflake database, the table did not appear following replication. Sometimes, it may take longer than expected for the table to show up. We are currently investigating this further. For now, a note has been added to continue to task 5 in case this error occurs, as from task 5, the tasks are independent and not blocked by this step.

### Testing Scope 

 Conducted end-to-end architecture validation, RBAC/policy checks, and instructions and screenshots enhancements.

---
</details>

<details>
  <summary>2025-07-31</summary>

## Infrastructure Changes

NA

## Content Changes
 
  - Instructions are enhanced for user better understanding.

## Screenshot Updates

  - Updated Enhanced screenshots with clear instructions.
  - Added numbers in the screenshots to follow step by step.

## Testing Notes

- **Testing Date**: 2025-07-31

---
</details>


<details>
  <summary>2025-05-16</summary>

## Infrastructure Changes

NA

## Content Changes

NA

## Screenshot Updates

  - **Getting Started**: Enhanced with an updated architecture diagram.
  - **Lab 01**: Improved guidance by refining steps and addressing display-related adjustments.
  - **Lab 02**: Clarified instructions to account for UI behavior and ensured accuracy in query details.
  - **Lab 03**: Structured action items with numbering for better readability.
  - **Lab 05**: Refined instructions to reflect accurate data handling and outputs.


## Testing Notes

- **Testing Date**: 2025-05-16

---
</details>

