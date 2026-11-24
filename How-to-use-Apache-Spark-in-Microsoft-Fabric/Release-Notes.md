# How to use Apache Spark in Microsoft Fabric

Welcome to the **How to use Apache Spark in Microsoft Fabric** Release-Notes.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-11-19</summary>

## Release Date: 2026-11-19

## Summary of Changes

Tested the **How to use Apache Spark in Microsoft Fabric** lab end to end against the current Microsoft Fabric portal and updated it. The getting-started guide and the Apache Spark, Dataflow Gen2, and Ingest Pipeline labs were updated where steps, dialog names, or screenshots no longer matched the portal.

## Infrastructure Changes
NA

## Content Changes

* **Getting started (gs-apache-spark.md):**
  * Updated the sign-in page heading to **Enter your work or school email, we'll check if you need to create a new account**.
  * Made the **Welcome to the Fabric view** dialog step optional, with a note that it doesn't appear for every account.
* **Lab 01: Apache Spark (01-apache-spark.md):**
  * Updated the trial activation dialog name to **Activate your 60-day free Fabric and Power BI trial**.
  * Added a note for the **Quickly expand and collapse** tip on the Workspaces pane.
  * Added a step to dismiss the new **FABRIC CAPACITY SETTINGS** tip.
  * Updated the workspace capacity selection to **capacity&lt;DeploymentID&gt;** and merged the workspace type, Details, and Apply actions into one step.
  * Made the **Introducing task flows** dialog step optional.
  * Added a step to use the back arrow after the service principal is added, to return to **Manage access**.
  * Updated the lakehouse step to clear the **Lakehouse schemas** checkbox, which is now selected by default.
  * Noted that the **Notebook Copilot Updates and Git Integration** dialog can take a few seconds to appear.
  * Explained why the generated **Load data** code fails with **UNRESOLVED_COLUMN** and told learners to replace it with the code in the guide.
  * Renamed every **+ Code** reference to **+ Add cell** to match the current notebook UI.
* **Lab 02: Dataflow Gen2 (02-dataflow-gen2.md):**
  * Updated the **New item** search steps, which no longer show a **Get data** section.
  * Added a note to dismiss the **Try the dynamic expression editor** tip.
  * Added a note that the **MonthNo** row starts unchecked with type **Any** until you set its Source type.
  * Added a note to click **Run** again if the pipeline doesn't start after **Save**.
  * Added numbered markers to the pipeline **Output** verification step.
* **Lab 03: Ingest Pipeline (03-ingest-pipeline.md):**
  * Replaced **My workspace** navigation with the **fabric-&lt;DeploymentID&gt;** workspace icon in four steps.
  * Updated the Copy assistant steps for the new **Copy job** wizard, including the **Url** field label.
  * Added notes on the **Row delimiter** default and choosing **Files** instead of **Tables** as the destination root folder.
  * Added a **Choose data destination** connection step that keeps the connection set to **(none)**.
  * Moved the notebook rename step to right after **Run all**, so learners no longer go back through the workspace.
  * Added a **Stop session** step with an Important note and Monitor cancel steps. If the notebook session stays open, the pipeline's Notebook activity never starts on the trial capacity.
  * Updated the lakehouse picker step to use the **OneLake catalog** tab.
  * Updated the **Base parameters** step. Fabric now auto-imports **table_name = sales**, so learners must change the value to **new_sales**.
  * Expanded the run duration note, including how to refresh the **Output** tab.
* Added `CHANGELOG-2026-11-19.md`, which lists every change and the screenshots the reviewer chose to keep.

## Screenshot Updates

* Replaced about 40 screenshots across the getting-started guide and **Labs 01 to 03** with current Microsoft Fabric UI captures. Each kept its original filename in the `Images` and `Images2` folders.
* Added new screenshots: `capacity-tip.png`, `back-arrow.png`, and `e3-dest-connection.png`.
* Refreshed screenshots for:
  * Sign-in and Temporary Access Pass
  * Trial activation
  * Workspace creation and access
  * Lakehouse upload
  * Notebook menus and output
  * Dataflow destination and pipeline activities
  * Copy job wizard steps
  * Delete data and Notebook activity settings
  * Table previews

## Testing Notes

* **Testing Date:** 2026-11-19

## Testing Scope

* Performed end-to-end testing of the **How to use Apache Spark in Microsoft Fabric** lab on a CloudLabs deployment in the live Microsoft Fabric portal.
* Validated the getting-started guide and the **Apache Spark, Dataflow Gen2, and Ingest Pipeline** labs against the current portal experience.
* Reproduced and documented the trial capacity issue where an open notebook session blocks the pipeline's Notebook activity, and verified the fix in the new Stop session step.
* Validated updated and newly added screenshots against their lab steps.
* Verified navigation, step order, and learner guidance across all affected exercises.

---
</details>
<details>
  <summary>2026-10-05</summary>

## Release Date: 2026-10-05

## Summary of Changes

Updated the **How to use Apache Spark in Microsoft Fabric** lab to align with the latest Microsoft Fabric user interface and current lab workflows. Instructions across the Apache Spark, Dataflow Gen2, and Ingest Pipeline labs were refreshed, and supporting screenshots were updated or added to provide accurate visual guidance for learners.

## Infrastructure Changes

* N/A

## Content Changes

* Updated **Lab 01: Apache Spark** instructions to reflect the latest Microsoft Fabric UI and workflow.
* Updated **Lab 02: Dataflow Gen2** instructions and navigation steps based on the current user experience.
* Updated **Lab 03: Ingest Pipeline** instructions to align with the latest UI and workflow.
* Updated the **Apache Spark getting-started** guidance with the latest instructions and navigation.
* Refreshed instructional content where the previous steps no longer matched the current Microsoft Fabric experience.
* Improved learner guidance and consistency across the affected lab exercises.

## Screenshot Updates

* Updated screenshots across **Labs 01–03** to match the latest Microsoft Fabric UI.
* Refreshed screenshots related to Apache Spark, Dataflow Gen2, Ingest Pipeline, and lab setup/navigation.
* Updated existing screenshots in the `Images2` folders.
* Added new screenshots to support updated instructions and workflows.
* Updated screenshots for environment, access, trial status, Fabric welcome experience, notebook, pipeline, and other UI workflows.

## Testing Notes

* **Testing Date:** 2026-10-05

## Testing Scope

* Performed lab testing for the **How to use Apache Spark in Microsoft Fabric** lab.
* Validated updated instructions against the latest Microsoft Fabric portal experience.
* Verified the updated workflows for **Apache Spark, Dataflow Gen2, and Ingest Pipeline**.
* Validated updated and newly added screenshots against the corresponding lab steps.
* Verified navigation, instructional sequence, and learner guidance across the affected exercises.
* Updated the lab documentation and screenshots based on findings identified during testing.

---

</details>

<details>
  <summary>09-June-2026</summary>

## Release Date : 09-June-2026

### Summary of Changes

Added additional steps to align with the latest lab workflow and updated the guide with screenshots reflecting the current UI. Successfully validated the lab by completing an end-to-end execution.

### Infrastructure Changes

### Content Changes

- Added note in Exercise - 1 > Task 3 (Name Error issue) to resovle that users need to check the missed commands to execute or re-run the commands from Task - 3 onwards.
- Added Lab Scenario to all exercise - 1,2,3

### Screenshot Updates

Screenshot were updated to reflect the latest UI in the following steps:
- Getting started page > Added new screenshots which helps to switch from powerBI page to Fabric page view and workspace type selection screenshot
- In Exercise - 2
    - Updated the UI in Task - 2 > step 5,6,7 to save & run the changes made to dataflow and rename to the dataflow name.
- Exercise - 3
    - In Task - 1 > updated the UI screenshot at step - (7 - 14) while creating copy data assistant pipeline, settings is added in pipeline.
    - In Task - 2 > second approach of creating a notebook from lakehouse workspace screenshot is added.
  
### Testing Notes

- **Testing Date**: 2026-06-08

### Testing Scope 

- Performed end to end lab, validated lab flow continuity, content accuracy, and screenshot alignment with the latest UI.

------------

</details>

<details>
  <summary>03-March-2026</summary>

## Release Date : 03-March-2026

### Summary of Changes

Added additional steps to align with the latest lab workflow and updated the guide with screenshots reflecting the current UI. Successfully validated the lab by completing an end-to-end execution.

### Infrastructure Changes

### Content Changes

- Added notes to Exercise 1 and Exercise 3 to provide clearer instructions.

### Screenshot Updates

Screenshot were updated to reflect the latest UI in the following steps:

- Exercise 1 > Task 2 > Step 1

### Testing Notes

- **Testing Date**: 2026-03-03

### Testing Scope 

- Performed end to end lab, validated lab flow continuity, content accuracy, and screenshot alignment with the latest UI.

------------

</details>

<details>
  <summary>04-February-2026</summary>

## Release Date : 04-February-2026

### Summary of Changes

Added additional steps to align with the latest lab workflow and updated the guide with screenshots reflecting the current UI. Successfully validated the lab by completing an end-to-end execution.

### Infrastructure Changes

### Content Changes

- Added notes to Exercise 1 and Exercise 2 to provide clearer instructions.
- Updated Exercise 3 – Task 1 step 11 -20 with new instructions aligned to the latest pipeline creation and data ingestion workflow.
- Revised Exercise 3 – Task 3 instructions to better match the current lab flow.

### Screenshot Updates

Screenshots were updated to reflect the latest UI in the following steps:
- Exercise 1 – Task 2 – Step 4
- Exercise 2 – Task 3 – Step 4
- Exercise 3 – Task 1, with additional images covering the updated pipeline creation flow.
- Exercise 3 – Task 3, updated few screenshots aligned to the latest UI.
### Testing Notes

- **Testing Date**: 2026-02-04

### Testing Scope 

- Performed end to end lab, validated lab flow continuity, content accuracy, and screenshot alignment with the latest UI.

------------

</details>

<details>
  <summary>22-August-2025</summary>

## Release Date : 22-August-2025

### Summary of Changes

Added explicit navigation steps in the lab guide and incorporated multiple screenshots to improve clarity and ensure correct environment access.

### Infrastructure Changes

### Content Changes

- Included explicit navigation steps to ensure users reach the correct development environment.

### Screenshot Updates

- Included multiple screenshots to enhance clarity.

### Testing Notes

- **Testing Date**: 2025-08-21

### Testing Scope 

Validation covered infrastructure compatibility, lab flow continuity, content accuracy, and screenshot alignment with the latest UI.

------------

</details>

<details>
  <summary>10-November-2025</summary>

## Release Date : 10-November-2025

### Summary of Changes

Minor updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.

### Infrastructure Changes
-  NA
### Content Changes

-  NA

### Screenshot Updates

- Minor updates:
  - Updated UI Screenshots: Replaced screenshots to match the latest user interface.
  - Instruction Refinements: Fixed rendering issues and added clear instructions.

### Testing Notes

- **Testing Date**: 2025-10-07

### Testing Scope 

Performed end to end lab testing, and all validations were successful. Updated lab guide for better clarity.

------------

</details>



