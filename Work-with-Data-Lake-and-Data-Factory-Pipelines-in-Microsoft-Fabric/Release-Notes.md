# Work with Data Lake and Data Factory Pipelines in Microsoft Fabric​

Welcome to the **Work with Data Lake and Data Factory Pipelines in Microsoft Fabric​** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-11-25</summary>

## Release Date: 2026-11-25

### Summary of Changes

Updated the Lab 01 (Use Delta tables in Apache Spark) and Lab 02 (Ingest data with a pipeline) guides and the lab overview page to match the current Microsoft Fabric UI. The update renames outdated UI terms and adds steps for new pop-ups and wizard pages.

### Infrastructure Changes

N/A

### Content Changes

**Lab Overview (overview-01.md)**
- Updated terminology to current Microsoft Fabric naming: OneLake, lakehouse, pipelines, and the Microsoft Fabric (Free) license prerequisite.
- Clarified the architecture and component descriptions; OneLake replaces the generic "Data Lake" component.
- Fixed wording in the Getting Started section, for example **Start, Stop, or Restart (2)** and "in the top-right corner".

**Lab 01 – Use Delta tables in Apache Spark**
- **Task 1 (Create a workspace):**
  - Clearer sign-in step and a conditional **Stay signed in?** step.
  - New step for the **Microsoft Fabric (Free) license assigned** pop-up.
  - Steps updated for the new left navigation.
  - **License mode** is now **Workspace type: Fabric**, **Advanced** is expanded by default, and **Add people and groups** is now **Add people or groups**.
- **Task 2 (Create a lakehouse and upload data):**
  - Added a New item filter step.
  - **Lakehouse Scheme** is now **Lakehouse schemas** (learners clear the checkbox).
  - Added a note about the new Context and SystemContext folders.
- **Task 3 (Explore data in a dataframe):**
  - **Skip tour** is now **Skip for now**.
  - Hover-then-ellipsis steps for **Load data**.
- **Task 4 (Create delta tables):**
  - **+ Code** is now **+ Add cell**.
  - The Explorer heading **Items** is now **OneLake**.
  - Hover-then-ellipsis step for **Copy ABFS path**.
- **Task 6 (Streaming):** Added a note to stop the Spark session before starting Lab 02.

**Lab 02 – Ingest data with a pipeline**
- **Task 1 (Create a pipeline):**
  - The **Copy data** wizard is now the **Copy job** wizard.
  - Steps now use the **OneLake catalog** tab.
  - New **Connection settings** step: leave it set to **(none)**.
  - **Row delimiter** now defaults to **Default (\r,\n, or \r\n)**.
  - Updated the **Settings**, **Map to destination**, **Review + save**, and **Create succeeded** steps.
  - Restored the **Run** and **Save and run** steps and the "Copy job connection is required" Note, which sends learners to Step 25 when there is no error.
  - The connection fix is a set of numbered steps: **Settings** > **Connection** > **Browse all** > **Copy job** > sign in > **Connect** > **Run** > **Save and run**.
- **Task 2 (Create a notebook):**
  - New first step to stop the Lab 01 Spark session from **Monitor**.
  - Added a troubleshooting note on **Run all**.
  - Updated the **+ Add cell**, **Toggle parameter cell**, and notebook **Settings** rename steps.
- **Task 3 (Modify the pipeline):**
  - The **Delete data** activity is now added from the **...** menu.
  - **Enable logging** is selected by default, so learners now clear it.
  - **Base parameters** now adds `table_name` automatically, so learners only change **Value** to `new_sales`.

### Screenshot Updates

All screenshots use the existing annotation style: 3 px red boxes on the element border, numbered corner badges, and a 2 px gray border. Deployment IDs, user names, and run IDs are blurred, and no mouse cursor is shown.

**Lab 01 – Use Delta tables in Apache Spark (12)**

| Screenshot | Task / Step | Change |
|---|---|---|
| `fab-ms-ex1-g1.png` | Task 1 – Enter sign-in details | Updated |
| `fab-license-popup.png` | Task 1 – Microsoft Fabric (Free) license assigned pop-up | **New** |
| `fabrichome.png` | Task 1 – Microsoft Fabric Home page and left navigation | Updated |
| `L1T1S6c-2506.png` | Task 1 – Workspaces > + New workspace | Updated |
| `L1T1S13.1-2302.png` | Task 1 – Create a workspace pane details | Updated |
| `L1T1S9-2506.png` | Task 1 – New empty workspace with task flows | Updated |
| `L1T2S1-2506.png` | Task 2 – + New item in the workspace | Updated |
| `L1T2S4-2506.png` | Task 2 – Lakehouse explorer view | Updated |
| `fab-ms-ex1-g19.png` | Task 3 – Notebook pop-up, Skip for now | Updated |
| `fab-ms-ex1-g20.png` | Task 3 – Files > products folder | Updated |
| `loaddata.png` | Task 3 – products.csv > ... > Load data | Updated |
| `E1T4S1.png` | Task 4 – + Add cell for the managed table | Updated |
| `cpabfs.png` | Task 4 – Files > ... > Copy ABFS path | Updated |

**Lab 02 – Ingest data with a pipeline (16)**

| Screenshot | Task / Step | Change |
|---|---|---|
| `L2T1S1-2506.png` | Task 1 – Open the workspace from the left navigation | Updated |
| `E1T4S8i.png` | Task 1 – Copy job wizard: verify sampled data settings | Updated |
| `l2T1S9a.png` | Task 1 – Choose data destination: Connection settings (none) | **New** |
| `E1T4S12.png` | Task 1 – File format settings | Updated |
| `l2T1S12.png` | Task 1 – Review + save | Updated |
| `L2T1S14-1709.png` | Task 1 – Create succeeded, Copy job on canvas | Updated |
| `upfab-ric-cor-g6.png` | Task 1 – Copy job connection: signed in, Connect | **New** |
| `l2T1S14.png` | Task 1 – Output tab, Pipeline status Succeeded | Updated |
| `L2T2-stopsession.png` | Task 2 – Monitor: stop the Lab 01 Spark session | **New** |
| `L2T2-stopconfirm.png` | Task 2 – Confirm stopping the Spark session | **New** |
| `ns-fab-g3.png` | Task 2 – Cell ... > Toggle parameter cell | Updated |
| `fab-ms-ex1-g46.png` | Task 2 – + Add cell below the parameters cell | Updated |
| `fab-ms-ex1-g50.png` | Task 2 – Notebook Settings: rename to Load Sales | Updated |
| `L2T3S4.2-2302.png` | Task 3 – Delete data activity Source settings | Updated |
| `L2T3S8b-2506.png` | Task 3 – Notebook activity settings and Base parameters | Updated |

### Testing Notes

- **Testing Date**: 2026-11-25

### Testing Scope 

- Performed end-to-end testing of the lab, and all validations completed successfully without any issues.
- Validated the updated lab instructions against the current Microsoft Fabric experience.
- Verified that updated screenshots align with the corresponding lab steps.
- Reviewed the lab guide for consistency, clarity, and minor content issues.
- No changes were introduced to the underlying lab functionality or dependencies.

---
</details>

<details>
  <summary>2026-09-18</summary>

## Release Date: 2026-09-01

### Summary of Changes

Updated Microsoft Fabric lab instructions and screenshots based on the current Fabric UI observed during lab testing. The changes remove outdated navigation steps, refresh screenshots, improve instructional clarity, and correct minor wording issues.

### Infrastructure Changes

N/A

### Content Changes

- Updated lab guide instructions to align with the current Microsoft Fabric experience.
- Made minor wording and formatting improvements for better clarity and consistency.
- Corrected minor instructional and typographical issues identified during lab testing.

### Screenshot Updates

- Updated relevant screenshots across the lab guide to reflect the current Microsoft Fabric UI.
- Replaced outdated screenshots with the latest UI references where applicable.

### Testing Notes

- **Testing Date**: 2026-09-17

### Testing Scope 

- Performed end-to-end testing of the lab, and all validations completed successfully without any issues.
- Validated the updated lab instructions against the current Microsoft Fabric experience.
- Verified that updated screenshots align with the corresponding lab steps.
- Reviewed the lab guide for consistency, clarity, and minor content issues.
- No changes were introduced to the underlying lab functionality or dependencies.
  
---
</details>

<details>
  <summary>2026-09-01</summary>

## Release Date: 2026-09-01

### Summary of Changes

The lab was successfully tested, and the content along with validations has been reviewed and updated.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Lab 01: Updated the screenshots to improve quality.

### Testing Notes

- **Testing Date**: 2026-08-31

### Testing Scope 

- Performed end-to-end testing of the lab, and all validations completed successfully without any issues.
  
---
</details>

<details>
  <summary>2026-07-31</summary>

## Release Date: 2026-07-31

### Summary of Changes

The lab was successfully tested, and the content along with validations has been reviewed and updated.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Lab 01: Updated the screenshots to improve quality.

### Testing Notes

- **Testing Date**: 2026-07-31

### Testing Scope 

- Performed end-to-end testing of the lab, and all validations completed successfully without any issues.
  
---
</details>

<details>
  <summary>2026-07-31</summary>

## Release Date: 2026-06-25

### Summary of Changes

Updated lab guide to align with the latest Fabric user interface and environment configuration. The workspace creation flow was revised to use the pre-provisioned Fabric F2 capacity instead of activating a Fabric Trial, navigation and pipeline creation steps were updated to match the current experience, and screenshots were refreshed accordingly. An additional note was added to handle common pipeline connection issues.

### Infrastructure Changes

- Due to issues encountered while creating Microsoft Fabric Trial capacities, the lab environment has been updated to provide learners with a pre-provisioned Microsoft Fabric F2 capacity.

### Content Changes

- Lab 01 – Task 1: Updated the workspace creation workflow to use the provided Fabric F2 capacity instead of activating a Fabric Trial. Also added steps to assign the required service principal as a Workspace Admin to ensure successful Validation.
- Lab 02 – Task 1: Updated the pipeline creation instructions to match the latest Microsoft Fabric interface and added troubleshooting guidance for the "Copy job connection is required" scenario.
- Lab 02 – Task 3: Updated navigation steps and Notebook activity insertion flow to reflect the current Microsoft Fabric experience. Updated terminology to use Copy job instead of Copy data where applicable.

### Screenshot Updates

- Lab 01 – Task 1: Refreshed screenshots for the updated workspace creation flow using Fabric F2 capacity and Workspace Admin configuration.
- Lab 02 – Task 1: Updated screenshots to reflect the latest pipeline creation experience. And refreshed with clear screenshots.
- Lab 02 – Task 3: Updated screenshots for Notebook activity configuration, pipeline navigation, and the renamed Copy job tile.

### Testing Notes

- **Testing Date**: 2026-06-25

### Testing Scope 

- Performed end-to-end validation of both labs using the updated Fabric F2 environment.
- Verified the revised workspace creation workflow and service principal assignment steps.
- Confirmed that refreshed screenshots and instructions match the latest Microsoft Fabric UI and that the labs execute successfully from start to finish.
  
---
</details>

<details>
  <summary>2026-05-14</summary>

## Release Date: 2026-05-14

### Summary of Changes

Updated the lab guide with the latest UI screenshots, revised the steps to reflect recent changes, corrected typographical errors, added lab scenarios, updated the summary pointers, and provided detailed explanations for each code snippet.

### Infrastructure Changes

N/A

### Content Changes

- Added lab scenarios, updated the summary pointers, and provided detailed explanations for each code snippet to improve clarity and understanding.
- **Lab 01, Task 1, Step 7**: Updated the terminology and labels to align with the latest UI changes and ensure consistency with the current application interface.
- **Lab 01, Task 1, Step 1**: Updated the step to align with the latest UI changes and ensure accuracy with the current interface workflow.
- **Lab 02, Task 1, Step 1, 2, & 3**: Corrected the step to accurately describe the process for creating and configuring a pipeline.

### Screenshot Updates

**Updated UI Screenshots**: 
  - **Lab 01, Task 1, Step 7** - Updated the screenshot as per latest UI.
  - **Lab 02, Task 1, Step 1, 2, & 3** - Updated the screenshots to provide clear guidance for users on creating and configuring a pipeline.
  - **Lab 01, Task 3, Step 1** - Updated the screenshot to reflect the latest UI changes and ensure consistency with the current application interface.

### Testing Notes

- **Testing Date**: 2026-05-14

### Testing Scope 

- Performed comprehensive end-to-end validation of the lab environment with successful execution across all test scenarios, refined the overall lab workflow to enhance usability and clarity, and updated the screenshots to align with the latest UI enhancements.
  
---
</details>

<details>
  <summary>2026-04-13</summary>

## Release Date: 2026-04-13

### Summary of Changes

Screenshots and instructions updated as per the UI updates in the Fabric portal. 

### Infrastructure Changes

N/A

### Content Changes

- **Lab 01**: Reflected Fabric UI updates; corresponding screenshots and instructions have been updated.

- **Lab 02**: As the Pipeline UI flow has changed, the steps and UI in Task 1 (creating a connection) have been updated. Based on Task 1, modifications were made to enhance the instructions in Task 3. In Task 2,the screenshots have been updated.

### Screenshot Updates

**Updated UI Screenshots**: 
  - **Lab 1**: Task 2 - Lake house search screenshot update.
  - **Lab 2**: Task 1 - Complete Screenshot change, Task 2 Step 1, Task 3 Step 2, Task 3 Step 4, Task 3 Step 4, Task 3 Step 8, Task 3 Step 9
    
### Testing Notes

- **Testing Date**: 2026-04-11

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully. Improved the lab flow for better clarity and refreshed the screenshots based on the latest UI changes.
---
</details>

<details>
  <summary>2026-02-23</summary>

## Release Date: 2026-02-23

### Summary of Changes

Screenshots and instructions updated as per the UI updates in the Fabric portal. 

### Infrastructure Changes

N/A

### Content Changes

- Updated screenshots on the Getting Started page.
- Reflected Fabric UI updates, including the license mode name change to Fabric Trial and minor updates in the Lakehouse UI; corresponding screenshots and instructions have been updated.
- In Lab 2, updated the steps and UI in Task 1 related to creating a Connection.

### Screenshot Updates

**Updated UI Screenshots**: 
  - Lab 1: Task 1 Step 1, Task 1 Step 8, Task 1 Step 9, Task 1 Step 11, Task 1 Step 13, Task 2 Step 2, Task 2 Step 7, Task 2 Step 9, Task 3 Step 1, Task 3 Step 7, Task 4 Step 1, Task 4 Step 3, Task 4 Step 4, Task 6 Step 6
  - Lab 2: Task 1 Step 1, Task 1 Step 7, Task 1 Step 8, Task 1 Step 12, Task 1 Step 13, Task 2 Step 1, Task 2 Step 7, Task 2 Step 8, Task 3 Step 2, Task 3 Step 4, Task 3 Step 4, Task 3 Step 8, Task 3 Step 9
    
### Testing Notes

- **Testing Date**: 2026-02-23

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully. Improved the lab flow for better clarity and refreshed the screenshots based on the latest UI changes.
---
</details>

<details>
  <summary>2026-01-16</summary>

## Release Date: 2026-01-16

### Summary of Changes

N/A

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: N/A
    
### Testing Notes

- **Testing Date**: 2026-01-16

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully. The lab guide was subsequently updated to enhance clarity and usability.

---
</details>


<details>
  <summary>2025-12-01</summary>

## Release Date: 2025-12-01

### Summary of Changes

This update includes minor improvements such as enhanced UI screenshots and revised instructions for better clarity and precision.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Screenshots have been replaced to align with the latest updates in the user interface.
    
### Testing Notes

- **Testing Date**: 2025-12-01

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully. The lab guide was subsequently updated to enhance clarity and usability.

---
</details>

<details>
  <summary>2025-06-18</summary>

## Infrastructure Changes

NA

## Content Changes

NA
  
## Screenshot Updates

NA

## Testing Notes

- **Testing Date**: 2025-06-18
- **Resolved Issues**: NA
---
</details>

<details>
  <summary>2025-06-12</summary>

## Infrastructure Changes

NA

## Content Changes

NA
  
## Screenshot Updates

- Minor screenshot updates to enhance overall user experience.

## Testing Notes

- **Testing Date**: 2025-06-12
- **Resolved Issues**: NA
---
</details>

<details>
  <summary>2025-09-01</summary>

## Release Date: 2025-09-01

### Summary of Changes

Minor updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.   

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced screenshots to match the latest user interface.
    - **Instruction Refinements**:Added clear instructions.
      
### Testing Notes

- **Testing Date**: 2025-09-01

### Testing Scope 

 Conducted end-to-end architecture validation, cost estimation checks, and prerequisite verification.

---
</details>





