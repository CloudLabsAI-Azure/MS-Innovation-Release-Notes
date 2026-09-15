# Snowflake Integration with Microsoft Fabric: Iceberg and Fabric Data Agent

Welcome to the **Snowflake Integration with Microsoft Fabric: Iceberg and Fabric Data Agent** release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, bug fixes and other relevant changes for the lab.

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
  <summary>2026-09-15</summary>

## Release Date: 2026-09-15

### Summary of Changes

Updated the complete **Snowflake Integration with Microsoft Fabric: Iceberg and Fabric Data Agent** workshop to improve technical accuracy, learner guidance, and alignment with the latest Microsoft Fabric and Snowflake user interfaces. Refined lab scenarios, task instructions, terminology, navigation steps, and screenshots across all five labs. Resolved the `DIM_CUSTOMER` data-loading issue caused by metadata columns in Lab 3 and updated the Snowflake Cortex Agent in Lab 5 to accurately reflect the limitations of self-service trial accounts.

### Infrastructure Changes

- **No infrastructure changes were made.** The updates are limited to lab content, documentation, screenshots, and learner guidance. No changes were made to the underlying lab provisioning, RBAC, resource configuration, or deployment infrastructure.

### Content Changes

* **Lab 1 – Microsoft Fabric Environment Setup**
  * **Task 2:** Removed redundant Fabric portal navigation steps because accessing the Fabric portal URL directly takes users to the required environment.
  * **Task 3:** Enhanced Lakehouse creation instructions with clearer guidance for workspace/location and capacity selection.
  * Added an optional notebook-based data exploration workflow with sample SQL/PySpark guidance.

* **Lab 2 – Snowflake and Fabric Integration with Iceberg**
  * **Task 1:** Updated Snowflake account creation instructions and clarified the required account configuration, including Enterprise Edition setup as per the latest UI updates in Snowflake.
  * **Task 2:** Improved Snowflake workspace and SQL file creation guidance.
  * **Task 3:** Restructured the External Volume and permissions configuration into clearer subsections and improved instructions for obtaining and configuring the required Azure tenant information.
  * **Task 3.3:** Improved Iceberg table creation instructions and SQL formatting.
  * **Task 3.4:** Added a notebook-based workflow to handle metadata columns generated with the Parquet files.
  * Added instructions to remove `METADATA$RL_ROW_ID` and `METADATA$RL_LAST_UPDATED_SEQUENCE_NUMBER` before creating the `dim_customer` Lakehouse table, resolving the Fabric Load to Tables wizard limitation.

* **Lab 3 – Real-Time Intelligence with Snowflake Integration**
  * Improved Eventstream and Eventhouse creation instructions and removed redundant navigation steps.
  * **Task 4:** Restructured the Microsoft Entra ID application registration and OAuth configuration steps with clearer permissions and navigation guidance.
  * Updated the Snowflake Catalog Database configuration and verification steps.

* **Lab 4 – Fabric Data Agents**
  * **Task 1:** Reworked the administrator configuration section as a **read-only activity**, clearly explaining that learners should review the required tenant settings but should not make changes.
  * **Task 2:** Improved Data Agent creation, workspace navigation, data source selection, testing, example query creation, and publishing instructions.
  * Added guidance for the **Skip for now** option in the Data Agent welcome dialog.
  * Added notes explaining that generated responses may vary.

* **Lab 5 – Snowflake Cortex for AI-Powered Analytics**
  * Updated the scenario and overview to focus on AI-powered analytics using Snowflake Cortex.
  * Updated terminology from **Semantic Model** to **Semantic View** to align with the current Snowflake experience.
  * **Task 1:** Updated Cortex Analyst navigation and semantic view creation steps to reflect the current Snowflake interface.
  * Updated the database and schema selection flow and clarified the creation of the `CUSTOMER_MODEL` semantic view using the `DIM_CUSTOMER` table.
  * **Task 2:** Updated Cortex Agent creation and configuration steps to reflect the current Agent Studio interface.
  * Added guidance for closing the **Agent readiness** dialog after creating the agent.
  * Updated the configuration flow to **Configuration → Tools → Add semantic view → Add → Save**.
  * Updated the Cortex Analyst tool configuration to use the `CUSTOMER_MODEL` semantic view.
  * Updated the Cortex Agent testing section to clearly explain that **Cortex Agent execution is unavailable in the Snowflake self-service trial environment used for the workshop**.
  * Added explicit guidance that learners should **not add a credit card or convert their trial account to a paid account** to enable Cortex Agent execution.
  * Converted the Cortex Agent testing portion into a **read-only/reference activity**, allowing learners to understand the expected experience without requiring paid Cortex capabilities.
  * Added and updated the workshop conclusion to summarize the combined Microsoft Fabric and Snowflake learning experience.

### Screenshot Updates

* Refreshed screenshots across the workshop to align with the latest Microsoft Fabric and Snowflake interfaces.
* **Lab 1**
  * Updated Fabric workspace, Lakehouse, and sample data loading screenshots.
  * Added screenshots supporting the updated Lakehouse and data-loading workflow.

* **Lab 2**
  * Updated Snowflake account creation and workspace screenshots.
  * Refreshed External Volume, permissions, and Iceberg table creation screenshots.
  * Added new screenshots for the notebook-based `DIM_CUSTOMER` data-cleaning and loading workflow.
  * Added visual guidance for removing the metadata columns before loading the data into the Lakehouse.

* **Lab 3**
  * Added and refreshed screenshots to align with the updated navigation and configuration steps.

* **Lab 4**
  * Refreshed screenshots for data source selection, testing, example query creation, and publishing.

* **Lab 5**
  * Updated Cortex Analyst screenshots to reflect the current **Semantic Views** experience.
  * Refreshed semantic view creation screenshots for database/schema selection, naming, table selection, and column selection.
  * Updated Cortex Agent creation and configuration screenshots to reflect the current Agent Studio interface.
  * Added a screenshot demonstrating the expected Cortex Agent execution limitation in the Snowflake self-service trial environment.
  * Added a reference screenshot demonstrating the expected Cortex Agent response experience in an environment where the required Cortex capabilities are enabled.

### Testing Notes

- **Testing Date**: 2026-09-11

### Testing Scope

Performed a comprehensive review of the complete five-lab workshop to validate the updated documentation, navigation flows, terminology, screenshots, and expected learner experience. . Reviewed screenshots and procedural steps to ensure that the documented instructions align with the current application interfaces and intended lab outcomes.

---
</details>

<details>
  <summary>2026-06-22</summary>

## Release Date: 2026-06-22

### Summary of Changes

Refined the lab documentation to improve usability and consistency across all modules. Replaced outdated visual references with current interface captures, enhanced instructional content for easier navigation, resolved formatting and display inconsistencies, and corrected content inaccuracies. Updated result and validation screenshots to ensure alignment with the latest application behavior and expected outcomes.

### Infrastructure Changes

- Updated the RBAC configuration at the Resource Group (RG) level by changing the assigned role from Contributor to Reader.

### Content Changes

* Added the **Lab Scenario**, **Architecture Overview**, **Architecture Diagram**, and **Component Explanations** to the **Getting Started** page.

* **Lab 1**

  * **Task 4, Step 8:** Corrected a typographical error.

* **Lab 2**

  * **Task 3.4, Step 10:** Updated the content to align with the latest changes in the Fabric Portal.
  * **Task 3.4, Step 12:** Added step numbering to match the screenshots.

* **Lab 3**

  * Renamed **Task 4** for improved grammatical accuracy.
  * **Task 1, Step 5:** Added a note to assist users who are unable to locate **Real-Time** in the navigation pane.
  * **Task 4, Step 16:** Added step numbering to align with the screenshot.

* **Lab 5**

  * **Task 1, Step 1:** Added step numbering to improve the user experience.
  * **Task 2, Step 1:** Added step numbering to improve the user experience.
  * **Task 2, Step 5:** Updated the content to reflect the latest UI changes.


### Screenshot Updates

* Updated the screenshots for the **Environment** tab on the **Getting Started** page.

* Added a screenshot at the bottom of each page to guide users on selecting Next and navigating to the subsequent lab.

* **Lab 1**

  * **Task 4, Step 6:** Updated the screenshot to reflect the latest UI changes.

* **Lab 2**

  * **Task 3.4, Step 5:** Added an additional screenshot to better align with the documented steps.

* **Lab 3**

  * **Task 1, Step 5:** Added a screenshot to assist users with the navigation process.
  * **Task 1, Step 6:** Updated the screenshot.
  * **Task 1, Step 8:** Replaced the screenshot with an updated version.

* **Lab 4**

  * **Task 2, Step 5:** Refreshed the screenshot to reflect the latest UI updates.
  * **Task 2, Example Query:** Replaced the screenshot with a clearer version to improve readability.

* **Lab 5**

  * **Task 1, Step 1:** Updated the screenshot to align with recent UI changes.
  * **Task 1, Steps 4–7:** Refreshed the screenshots to improve image quality and clarity.
  * **Task 2, Step 1:** Updated the screenshot for better clarity.
  * **Task 2, Steps 5–6:** Updated the screenshots to reflect the latest UI changes.
  * **Task 2, Step 9:** Updated the screenshot to align with recent UI updates.

  
### Testing Notes

- **Testing Date**: 2026-06-22

### Testing Scope 

Performed a comprehensive review of all lab exercises to validate the latest documentation updates and ensure consistency across the learning experience. Confirmed that all task instructions, expected outcomes, and navigation flows function as intended. Verified data ingestion and processing scenarios, reviewed guidance provided throughout the labs, validated Snowflake integration workflows and Cortex Agent exercises, and ensured that all screenshots accurately reflect the current product interface and corresponding procedural steps.

---
</details>

<details>
  <summary>2026-04-30</summary>

## Release Date: 2026-04-30

### Summary of Changes

Enhanced lab content by updating UI screenshots to reflect the latest interface and improving step-by-step instructions for greater clarity. Standardized database names, corrected spelling errors, and fixed rendering issues. Added updated output screenshots to align with the latest results.

### Infrastructure Changes

N/A

### Content Changes

- Improved and clarified instructions across various labs
- Lab 1, Task 4, Step 5 (Fabric Portal) - Change in Database names, and also modified the output window.
- Lab 2, Task 1, Step 5 and Step 6 (Snowflake Portal) - Blurred out unique IDs.
- Lab 3, Task 1, Step 17, Task 2, Step 3, Task 4, and Step 13 (Fabric Portal) - Blurred out unique IDs.
- Lab 4, Task 2, Step 2 (Fabric Portal) - Updated the UI screenshot.
- Lab 5, Task 1, Step 1 (Snowflake Portal) - Updated spelling mistakes and updated screenshot.
- Lab 5, Task 2, Step 11 (Snowflake Portal) - Updated screenshot as per the updated name.
- Lab 5, Task 3, Step 12 (Snowflake Portal) - Added a output screenshot for better clarity.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI and improve user understanding:
- Updated screenshots in Lab 1 (Fabric Portal) to reflect the changes made in the database names, and also added new output screenshots.
- Updated screenshots to blurr out user IDs and other unique IDs.
- In Lab 5 (Snowflake Portal), updated UI screenshots to reflect the latest changes. Also added new screenshot to reflect the latest output.
  
### Testing Notes

- **Testing Date**: 2026-04-30

### Testing Scope 

Revalidated all labs through end-to-end testing to ensure updated instructions are accurate and the user experience is seamless. Verified Lakehouse data loading workflows, tested troubleshooting guidance, and confirmed the correctness of Snowflake-related tasks, including Cortex Agent functionality. Ensured all screenshots are aligned with the latest UI and documented steps.

---
</details>

<details>
  <summary>2026-04-09</summary>

## Release Date: 2026-04-09

### Summary of Changes

Enhanced the lab content by updating UI screenshots to reflect the latest interface and improving step-by-step instructions for better clarity. Added guidance to help users troubleshoot common errors encountered while loading data into the Lakehouse. Also introduced instructions on how to set up and use the Snowflake trial environment effectively.

### Infrastructure Changes

N/A

### Content Changes

- Improved and clarified instructions across Lab 1, Lab 2, Lab 3, Lab 4, and Lab 5 to enhance readability and ease of execution.
- Updated content to align with the latest UI changes across the platform.
- Added troubleshooting notes to assist users in resolving errors during data loading in the Lakehouse.
- Included additional guidance in Lab 5 (Task 3) for working with the Cortex Agent.
- Added instructions for setting up and using the Snowflake trial environment.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI and improve user understanding:
- Updated screenshots in Lab 5 to align with the latest Cortex Search UI changes in Snowflake.
- Added new screenshots in Lab 2 to provide a more guided and user-friendly experience.

### Testing Notes

- **Testing Date**: 2026-02-12

### Testing Scope 

Performed end-to-end testing of all labs to validate updated instructions and ensure a smooth user experience. Verified data loading workflows in the Lakehouse, tested troubleshooting steps, and confirmed accuracy of the Snowflake-related tasks, including Cortex Agent functionality. Ensured all screenshots are consistent with the latest UI and documented steps.

---
</details>

<details>
  <summary>2026-02-12</summary>

## Release Date: 2026-02-12

### Summary of Changes

Made updates by adding clearer, updated UI screenshots and enhanced instructions for clarity.

### Infrastructure Changes

N/A

### Content Changes

- Lab 01: Added instructions for Task 3 and Task 4 for better clarity.
- Lab 02: Added instructions for Task 1, Task 3.1, Task3.2, and Task 3.4 for better clarity.
- Lab 03: Added instructions for Task 1 and Task 4 for better clarity.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI in the following steps:
- Updated the Screenshorts for the Getting Started page with the latest UI
- Lab 01  – Task 1 - Steps 1,3
- Lab 01  – Task 2 - Steps 1,5
- Lab 01  – Task 3 - Step 1
- Lab 01  – Task 4 - Steps 5,13,14
- Lab 02  – Task 1 - Steps 1,2,
- Lab 02  – Task 3 -Task 3.1 - Step 2
- Lab 02  – Task 3 -Task 3.2 - Step 5
- Lab 02  – Task 3 -Task 3.3 - Step 3
- Lab 02  – Task 3 -Task 3.4 - Step 5,12
- Lab 03  – Task 1 - Steps 5,7,8
- Lab 03  – Task 2 - Steps 1,7,8
- Lab 03  – Task 3 - Steps 1,3,4
- Lab 03  – Task 4 - Steps 3,6
- Lab 04  – Task 2 - Add an Example Query - step 1

### Testing Notes

- **Testing Date**: 2026-02-12

### Testing Scope 

  Performed complete testing of the lab and updated screenshots and steps for clarity. 

---
</details>

<details>
  <summary>2026-01-13</summary>

## Release Date: 2026-01-13

### Summary of Changes

Need to Provide RBAC Application Developer role on Tenant to the user explicitly. Updated screenshots and instruction.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Updated UI Screenshots**: N/A.

### Testing Notes

- **Testing Date**: 2026-01-13

### Testing Scope 

Conducted end-to-end validation and prerequisite verification.
</details>

<details>
  <summary>2025-10-29</summary>

### Summary of Changes

Updated the lab by including the latest, clearer UI screenshots and refining the instructions to enhance clarity, accuracy, and ensure a seamless learning experience. 

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Updated UI Screenshots**: Updated screenshots to align with the latest user interface.

### Testing Notes

- **Testing Date**: 2025-10-29

### Testing Scope 

Conducted end-to-end validation and prerequisite verification.
</details>












