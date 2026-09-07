# Migrate and Modernise SQL Servers to Azure
Welcome to the **Migrate and Modernise SQL Servers to Azure** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-09-03</summary>

## Release Date: 2026-09-03

### Summary of Changes

Performed end-to-end validation and content updates for the **Migrate and Modernize SQL Servers to Azure** lab to replace tooling retired by Microsoft — **Data Migration Assistant (DMA)** and **Azure Data Studio (Azure SQL Migration extension)** — with the currently supported flow using **SQL Server Management Studio (SSMS)** and the **Azure Portal-based Azure Database Migration Service (DMS)**. Updates include revised migration workflows, a new Blob Storage upload task, corrected task numbering and naming, refreshed architecture diagrams, and presentation deck alignment.

### Infrastructure Changes

N/A

### Content Changes

- **Getting Started Page**: Removed DMA references from the Lab Scenario, Objective bullets, and Architecture section; updated Lab 2 and Lab 3 descriptions to reflect the SSMS and Portal-based DMS workflows.
- **Lab 01 - Exercises 02 & 03**: Minor typo and capitalization fixes; no tooling changes required.
- **Lab 02 - Task 02**: Replaced the DMA assessment with an SSMS-based schema audit query; added the missing Connect to Server step; removed the .NET Framework/DMA install note; standardized the SSMS version to SSMS 22.
- **Lab 02 - Task 04**: Replaced the DMA schema migration with the SSMS Generate Scripts wizard (Azure SQL Database engine type, script cleanup, `USE parts` context); added a DACPAC alternative.
- **Lab 02**: Reordered tasks so Retrieve connection information precedes schema migration; moved the "minimize SQLVM connection" note to the end of Task 4; removed remaining DMA wording from Task 5 and the DMS description.
- **Lab 03 - Task 05 (New)**: Added Upload the backup to Azure Blob Storage and assign the Storage Blob Data Reader permission to the SQL Managed Instance and the ODL user.
- **Lab 03 - Task 06**: Replaced the Azure Data Studio migration project with the Azure Portal DMS online migration wizard (Blob storage backup source).
- **Lab 03 - Task 07**: Moved the `INSERT` / `BACKUP LOG` steps from Azure Data Studio to SSMS; added `.trn` upload-to-Blob steps and a beginner-friendly explanation of transaction log status progression.
- **Lab 03**: Corrected the service account from `sqlmiuser` to `demouser`; renumbered tasks 1–8; fixed heading levels; updated the DMS description from SMB share monitoring to Blob Storage monitoring; removed DMA from the Conclusion.
- **Presentation Deck**: Replaced the DMA row with SSMS (Slide 8); replaced the DMA-based Migration Overview diagram with the SSMS + DMS flow (Slide 15); updated Lab 2 Task 4 to reference SSMS (Slide 26); corrected `sqlmiuser` → `demouser`, added the Blob Storage task, and renumbered tasks 5–8 (Slide 27); replaced the retired DMA documentation link with the SSMS Migrate SQL Server Microsoft Learn link (Slide 29).

### Screenshot Updates
- Added the updated screenshots all over the lab
- Added new screenshots for the SSMS Generate Scripts wizard, script cleanup, Azure SQL Database connection, and schema verification (**Lab 02**).
- Added new screenshots for Blob Storage container creation, backup/`.trn` upload, IAM role assignment, and the Portal-based DMS online migration wizard (**Lab 03**).
- Updated the **Architecture Diagram** to remove DMA, reflect the SSMS schema migration, and show the corrected Lab 3 flow including the Blob Storage upload step.

### Validation

- N/A

### Testing Notes

- **Testing Date**: 2026-09-03

### Testing Scope

- Deployed a fresh lab instance and completed end-to-end validation of the updated flow.
- Verified SSMS-based assessment and schema migration to Azure SQL Database.
- Verified Portal-based DMS online migration to Azure SQL Managed Instance, including Blob Storage upload, transaction log restore, and cutover.
- Validated task numbering, headings, naming conventions, and formatting across all lab guides.
- Confirmed the presentation deck matches the updated lab guides; package validation passed with theme and formatting unchanged.

---
</details>

<details>
  <summary>2026-08-03</summary>

## Release Date: 2026-08-03

### Summary of Changes

Performed end-to-end testing of the **Migrate and Modernize SQL Servers** to Azure lab to validate the complete migration workflow against the latest Azure Migrate experience and ensure the accuracy and consistency of the lab instructions.

### Infrastructure Changes

- N/A

### Content Changes

- N/A

### Screenshot Updates

- N/A

### Validation

- N/A

### Testing Notes

- **Testing Date**: 2026-08-03

### Testing Scope

- Performed end-to-end testing of the lab.
- Verified the migration workflow and lab instructions for accuracy and consistency.
- Confirmed that all exercises function as expected with the latest Azure Migrate experience.

---
</details>

<details>
  <summary>2026-06-09</summary>

## Release Date: 2026-06-09

### Summary of Changes

Performed end-to-end validation and content updates for the **Migrate and Modernize SQL Servers to Azure** lab to align with the latest Azure Migrate experience, improve instruction clarity, and ensure consistency throughout the migration workflow. Updates include UI refreshes, refined guidance, migration flow improvements, SQL Server version updates, screenshot enhancements, and formatting corrections.

### Infrastructure Changes

N/A

### Content Changes

- **Getting Started Page**: Updated the environment screenshots to align with the latest lab environment UI.
- **Lab 01 - Exercise 01**: Updated Azure Migrate screenshots to match the latest UI and refined the instructions for improved clarity.
- **Lab 01 - Exercise 02**: Refined instructions and updated the assessment workflow to align with the latest Azure Migrate experience.
- **Lab 01 - Exercise 03**: Updated storage account creation screenshots and revised the migration workflow to reflect the latest Azure portal UI.
- **Lab 02 - Exercises 01 & 02**: Updated references from SQL Server 2008 to SQL Server 2022, refined instructions to align with the current workflow, masked sensitive information, and corrected numbering and formatting issues.

### Screenshot Updates

- Updated screenshots across the **Getting Started Page**, **Lab 01**, and **Lab 02** to align with the latest Azure portal and Azure Migrate UI.
- Updated assessment, storage account creation, and migration workflow screenshots.
- Masked sensitive information in applicable screenshots.

### Validation

- N/A

### Testing Notes

- **Testing Date**: 2026-06-09

### Testing Scope

- Completed end-to-end validation of the lab.
- Verified the updated Azure Migrate assessment and migration workflows.
- Validated all revised instructions, numbering, and formatting changes.
- Confirmed screenshots align with the latest Azure portal experience.
- Ensured consistency, readability, and accuracy across all exercises.

---
</details>

<details>
  <summary>2026-05-20</summary>

## Release Date: 2026-05-20

### Summary of Changes

Performed end-to-end validation and content updates for the **Migrate and Modernize SQL Servers to Azure** lab to improve clarity, consistency, and learner experience. Updates include refined step instructions, addition of missing task descriptions, standardized completion messaging, and enhanced screenshots aligned with the latest Azure lab environment.

### Infrastructure Changes

N/A

### Content Changes

- **Getting Started Page**: Updated environment screenshots to align with the latest Azure lab UI.  
- **Lab 01 - Exercise 01 Task 01**: Added task description, refined instructions for clarity, masked sensitive lab code in screenshots, and standardized completion message.  
- **Lab 01 - Exercise 02 Task 01**: Improved step clarity, corrected numbering inconsistencies, and updated completion messaging.  
- **Lab 01 - Exercise 03 Tasks**: Fixed image alignment, spacing, and numbering; added missing task descriptions to improve readability.  
- **Lab 02 - Exercise 01**: Added task descriptions and restructured steps with clear numbering for better flow.  
- **Lab 02 - Exercise 02**: Enhanced screenshot clarity and masked sensitive details (Tenant ID/DID) across steps.  
- **Lab 02 - Conclusion**: Added a structured conclusion section and improved overall exercise continuity.  
- **All Labs**: Standardized completion message across exercises for consistency in learner experience.  

### Screenshot Updates

- Updated and improved screenshots across **Getting Started Page, Lab 01, and Lab 02** for clarity and consistency.
- Added image borders, spacing adjustments, and formatting improvements for better readability.
- Masked sensitive information (Lab codes, Tenant IDs, DID values) in screenshots.

### Validation
- NA

### Testing Notes

- **Testing Date**: 2026-05-20

### Testing Scope 

- Completed full end-to-end testing of the lab.
- Validated all steps, numbering, and instructions for accuracy.
- Verified screenshots align with the current Azure lab environment.
- Ensured improved readability, consistency, and security compliance across the lab guide.

---
</details>

<details>
  <summary>2026-05-15</summary>

### Release Date: 2026-05-15
  
- **Testing Date**: 2026-05-15

## Infrastructure Changes
- NA

## Content Changes
- **Getting Started Page**: Added Lab Scenario and updated Task 6 content.
- **Exercise 1–6**: Refined instructions, improved navigation, fixed numbering, added notes, and aligned steps with latest UI.
- Reorganized steps and improved task flow for better learner experience.
- Applied confidentiality adjustments where needed.

## Screenshot Updates
- Updated screenshots across **Getting Started Page and Exercises 1–6** to match latest UI.
- Replaced unclear images and added better visual guidance.

## Validation
- All exercises validated successfully with no blocking issues.

## Testing Notes
- Completed end-to-end testing and ensured accuracy, consistency, and improved usability.

---
</details>

<details>
  <summary>2026-01-29</summary>

### Release Date: 2025-09-08
  
- **Testing Date**: 2026-01-28

## Infrastructure Changes

 - NA

## Content Changes

  - **Azure Migrate** service UI has completely rolled out to new UI and navigation steps are changed. Checked all the labs and updated the instructions as per the new UI along with updated screenshots for better clarity and precision.

## Screenshot Updates

   - **Updated UI Screenshots**: Screenshots have been replaced to align with the latest updates in the user interface.

## Validation

   We have validation issue in Exercise 2 due to recent UI changes, after checking with engineering team we have removed the validation in Exercise 2 for time being as we are working with MS support team and engineering team to fix it. Once fixed the validation will be re-added.

## Testing Notes

- Completed end-to-end lab testing with all validations passing successfully. The lab guide was subsequently updated to enhance clarity and usability.

---
</details>

<details>
  <summary>2025-09-08</summary>

### Release Date: 2025-09-08
  
- **Testing Date**: 2025-09-08

## Infrastructure Changes

 - Updated the image of Appliance VM. Updated ip configurations to static.

## Content Changes

  - HOL 1 Exercise 3 Task 4 was incomplete, added it.

## Screenshot Updates

  - **Change**: Updated almost all the screenshots for the whole lab for enhancement.

## Validation

   NA

## Testing Notes

- **Test Validation Summary**: Validated the lab guide steps, updated the screenshots for enhancement.

---
</details>

<details>
  <summary>2025-05-26</summary>

### Release Date: 2025-05-26
  
- **Testing Date**: 2025-05-26

## Infrastructure Changes

   NA

## Content Changes

  - There has been a UI update in Microsoft Azure for the Migration Wizard. Therefore, the lab guide for **Module 3** has been updated accordingly.

## Screenshot Updates

  - **Change**: Updated almost all the screenshots for the whole lab to reflect the latest UI changes in the Environment and also the Azure portal.

## Validation

   NA

## Testing Notes

- **Test Validation Summary**: Validated the lab guide steps, updated the content to reflect the latest UI changes, and reorganized exercises for better alignment with the overall lab flow.

---
</details>
