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

Updated the lab, Migrating SQL Databases to Azure lab to align with the latest migration workflow by replacing Azure Data Studio with SQL Server Management Studio (SSMS) 22, introducing new hands-on exercises, enhancing migration guidance, and refreshing screenshots throughout the lab. The updates provide a more streamlined and realistic migration experience for learners.

### Infrastructure Changes

N/A

### Content Changes

- Replaced Azure Data Studio-based instructions with SQL Server Management Studio (SSMS) 22 throughout the lab.
- Added a new Exercise 1 focused on performing database assessments.
- Added detailed steps for connecting to the virtual machine using RDP.
- Added instructions for configuring Service Broker and updating database recovery models.
- Added assessment validation and migration readiness guidance.
- Added a new Exercise 2 covering end-to-end migration of the WideWorldImporters database to Azure SQL Managed Instance.
- Added steps to create and configure an SMB network share.
- Added instructions to update the MSSQLSERVER service account to use the lab user account for backup operations.
- Added detailed database backup and transaction log backup procedures.
- Added Azure Blob Storage upload instructions for migration files.
- Added Storage Blob Data Reader permission assignment steps for the user account and SQL Managed Instance managed identity.
- Added detailed Azure Database Migration Service (DMS) online migration steps, including migration creation, monitoring, synchronization, and cutover.
- Added post-migration verification and validation steps using SSMS.
- Removed outdated MFA walkthrough content from the main lab guide.
- Added a VM resizing tip to improve the learner experience during lab execution.
- Improved instruction clarity and overall lab flow across multiple exercises.

### Screenshot Updates

- Updated screenshots throughout the main lab guide to align with the latest Azure portal experience.
- Added new screenshots supporting the database assessment workflow in Exercise 1.
- Added new screenshots supporting Azure SQL Managed Instance migration activities in Exercise 2.
- Updated screenshots related to Azure Database Migration Service configuration and monitoring.
- Added new screenshots demonstrating SMB share creation and backup configuration steps.
- Updated Azure portal and environment-related screenshots to reflect the current user experience.
- Added new screenshots to Exercise 7 (taskstep-1.png and taskstep-2.png).
- Added a large collection of new media assets, including labguide.png, environment.png, azureportal.png, and multiple task-related screenshots.

### Testing Notes

- Testing Date: 2026-09-07

### Testing Scope

- Conducted end-to-end validation of the updated lab experience.
- Verified all newly added Exercise 1 instructions and assessment workflows.
- Verified all newly added Exercise 2 migration steps and task sequencing.
- Validated backup, SMB share, Azure Blob Storage, and DMS migration workflows.
- Confirmed all screenshots match the current portal and lab experience.
- Reviewed image references, formatting, and content consistency across all lab guides.
- Ensured successful post-migration validation steps using SQL Server Management Studio (SSMS) 22.

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

