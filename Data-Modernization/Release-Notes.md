# Data Modernization

Welcome to the **Data Modernization** release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, bug fixes, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

 `Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-09-07</summary>

## Release Date: 2026-09-07

### Summary of Changes

Updated the lab guides to align with the latest migration workflow by replacing Azure Data Studio with SQL Server Management Studio (SSMS) 22. The lab was enhanced with new assessment and migration exercises, updated screenshots, improved learner guidance, and a modernized migration experience that reflects current Azure SQL Managed Instance migration practices.

### Infrastructure Changes

- Updated the lab environment template to include SQL Server Management Studio (SSMS) 22.
- Removed the dependency on Azure Data Studio from the lab workflow.

### Content Changes

- Replaced Azure Data Studio with SQL Server Management Studio (SSMS) 22 across the lab and updated the overall migration workflow to align with current best practices.
- Created a new Exercise 1 focused on database assessment and migration readiness, including RDP connectivity, Service Broker configuration, recovery model updates, and assessment validation.
- Created a new Exercise 2 providing an end-to-end migration experience from SQL Server to Azure SQL Managed Instance, including backup creation, Azure Blob Storage integration, migration setup, cutover, and validation.
- Added detailed guidance for SMB share creation, SQL Server service account configuration, backup generation, and required permission assignments for migration activities.
- Enhanced the lab with Azure Database Migration Service (DMS) online migration instructions, including migration configuration, monitoring, synchronization, and post-migration verification using SSMS.
- Refined the overall learner experience by removing outdated guidance, adding a VM resizing tip, improving task sequencing, and updating instructional content to match the new migration approach.

### Screenshot Updates

- Updated screenshots across the main lab guide and refreshed Azure portal/environment visuals to align with the latest user experience.
- Added new screenshots supporting Exercise 1 database assessment tasks and Exercise 2 Azure SQL Managed Instance migration workflows, including SMB share configuration, backups, and Azure Database Migration Service (DMS) activities.
- Added new media assets and supporting screenshots throughout the lab, including Exercise 7 updates (taskstep-1.png and taskstep-2.png), to improve visual guidance and learner clarity.

### Testing Notes

- Testing Date: 2026-09-07

### Testing Scope

- Performed end-to-end lab testing of the complete lab workflow, including all updated exercises and migration scenarios.
- Validated Exercise 1 assessment activities and Exercise 2 migration workflows, including backups, storage configuration, Azure Database Migration Service (DMS), cutover, and post-migration verification using SSMS 22.
- Confirmed that all screenshots, image references, instructional content, task sequencing, formatting, and learner guidance are accurate and consistent throughout the lab guides.

---

</details>
<details>
  <summary>2026-05-21</summary>

## Release Date: 2026-05-21

### Summary of Changes

The lab was successfully tested, and the instructions and screenshots were updated accordingly. 
### Infrastructure Changes

N/A

### Content Changes

- Added a detailed lab scenario and incorporated the required prerequisites to improve clarity and setup readiness.
- E2, T2, S2 - Updated the steps to reflect the latest UI changes.
- E3, T5, S2 - Added an additional note to guide users in case they encounter login issues.
- E3, T5, S4 - Added step numbering to align with the screenshots.
- E3, T5, S9 - Added an additional note explaining how to retrieve the Authentication Key from the Azure portal in case users encounter any issues.
- E4, T1, S9, S10, S11 - Added step numbering to align with the screenshots.

### Screenshot Updates

- Updated the screenshot on the **Getting Started** page for the **Environment** tab to reflect the latest UI changes.
- E2, T1, S5 - Updated the screenshot to reflect the latest UI changes.
- E3. T5, S2 - Updated the screenshot to reflect the latest UI changes.
- E3, T5, S9 - Added screenshots to the additional note to help guide users through the exercise.

### Testing Notes

- **Testing Date**: 2026-05-21

### Testing Scope

Conducted end-to-end lab testing and updated the instructions and screenshots accordingly.

---
</details>

<details>
  <summary>2026-01-21</summary>

## Release Date: 2026-01-21

### Summary of Changes

The lab has been successfully tested, and the lab content has been reviewed and validated.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated Screenshots**: Updated screenshots with respective instructions.

### Testing Notes

- **Testing Date**: 2026-01-21

### Testing Scope

Performed end-to-end lab testing and validations, updating instructions and screenshots.

---
</details>

<details>
  <summary>2026-01-08</summary>

## Release Date: 2026-01-08

### Summary of Changes

The lab has been successfully tested, and the lab content, along with validation, has been reviewed and updated.  

### Infrastructure Changes

N/A

### Content Changes

Ex 2 - added steps to enable SAMI on VM and add role assignment as it is required now to run online migration. 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated a few of the screenshots as per new content.
      
### Testing Notes

- **Testing Date**: 2026-01-07

### Testing Scope 

 Conducted end-to-end testing, updated the custom policy, and verified it.

---
</details>

<details>
  <summary>2025-09-19</summary>

## Release Date: 2025-09-19

### Summary of Changes

The lab has been successfully tested, and the lab content, along with validation, has been reviewed and updated.  

### Infrastructure Changes

N/A

### Content Changes

Exercise 2 - updated the steps as per the new UI in Azure Data Studio.

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated a few of the screenshots as per new content.
      
### Testing Notes

- **Testing Date**: 2025-09-18

### Testing Scope 

 Conducted end-to-end testing, RBAC/policy, and validation checks.

---
</details>

