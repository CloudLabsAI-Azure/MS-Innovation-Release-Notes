# Fabric Analytics in a Day

Welcome to the **Fabric Analytics in a Day** Readme.md. In this, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots,[...]

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes
<details>
  <summary>2026-08-21</summary>

## Release Date: 2026-08-21

### Summary of Changes
Updated Fabric Analyst in a Day Labs 1–7 to reflect current Azure Portal and Fabric UI behavior. Added new guidance notes (Power BI Desktop responsiveness, Get Data experience popup), clarified numerous step instructions across ingestion, pipeline, semantic modeling, and reporting tasks, and refreshed a large number of screenshots to match the current portal experience. Lab 5 also received new logic documentation explaining the Until-loop pipeline architecture.

### Infrastructure Changes
N/A

### Content Changes
- Lab-1.md
  - Added note about a Power BI Desktop responsiveness issue, with focus mode instructions and supporting screenshots.
  - Added note about the "Introducing the new Get Data experience" popup.
- Lab-2.md
  - Task 1 (Enable Fabric Trial): Simplified login flow with updated credentials guidance.
  - Task 2 (Create Workspace): Updated license mode selection instruction; added note about the Task flows dialog.
  - Tasks 4-10: Replaced multiple outdated image references with current Azure UI screenshots.
- Lab-3.md
  - Task 1: Clarified UI navigation with numbered callout references; updated shortcut connection wording ("In the Connection dropdown, select..." replacing "Click on Create New Connection").
  - Task 2: Repositioned the visual query note with a supporting screenshot; added explicit "scroll right before clicking double arrow" instruction; updated ribbon navigation wording (Home → Manage columns → Choose columns); added checkpoint note confirming the Geo query should have 14 columns.
  - Task 3: Updated the new SQL query screenshot reference.
- Lab-4.md
  - Tasks 1–3: Updated screenshot references; added note about expanding the ribbon menu.
  - Task 3: Clarified "Expand lh_FAIAD" and "Then select dbo" wording.
  - Task 4: Updated Save & Run workflow step numbering; added instruction to refresh tables to view newly created tables.
  - Tasks 5-8: Consistent wording and screenshot reference updates.
  - Task 10: Clarified "provide access to the Customer table" wording; added an [IMPORTANT] note distinguishing the Customer (Dataverse) table from the Customers (ADLS) table.
- Lab-5.md
  - Task 1: Minor wording updates (commas, article usage); updated refresh settings step numbering and pipeline scheduling screenshots.
  - Task 5 (NEW): Added a comprehensive flow diagram and logic documentation explaining the Until-loop architecture before the task steps begin, plus a table mapping each task to its role in the loop.
  - Tasks 5–13: Updated activity configuration instructions with numbered step references; enhanced variable and expression builder instructions with corrected grammar.
- Lab-6.md
  - Task 1: Removed the "Minimize the task flow" instruction (no longer applicable) and the redundant "Open semantic model" step.
  - Task 6: Updated checkpoint formatting; added a new relationship diagram screenshot.
  - Task 7: Added a step to expand Measures in Model view.
- Lab-7.md
  - Task 1: Added screenshots for the auto-create report and save steps.
  - Task 2: Updated report creation and format page steps with numbered references.
  - Task 3: Added a text box creation screenshot.
  - Task 6: Added a save steps screenshot.
  - Task 8: Updated sort/visual configuration wording ("Sort axis" → "Sort by").
  - Task 11: Updated shortcut creation process with new screenshots.

### Screenshot Updates

- Lab 1
  - L1T2S8a-1908.png, L1T2S8b-1908.png - Task 2: illustrates the Power BI Desktop focus-mode workaround for the responsiveness issue.
  - L1T3S1note-1908.png - Task 3: shows the new "Introducing the new Get Data experience" popup referenced in the added note.
- Lab 2
  - L2T1S2-1908.png, L2T1S6-1908.png, L2T1S7-1908.png, L2T1S8-1908.png - Task 1 (Enable Fabric Trial): reflect the simplified login flow and updated credentials guidance.
  - L2T2S8-1908.png - Task 2 (Create Workspace): shows the Task flows dialog called out in the new note.
  - L2T4S1-1908.png through L2T10S2-1908.png - Tasks 4-10: bulk replacement of outdated screenshots with current Azure UI across these tasks.
- Lab 3
  - L3T2S5note-1908.png - Task 2: supports the repositioned visual query note.
  - L3T2S12-1908.png - Task 2: shows the "scroll right before clicking double arrow" step.
  - L3T2S20-1908.png - Task 2: supports the checkpoint note confirming the Geo query has 14 columns.
  - L3T2S23-1908.png - Task 2: shows the updated ribbon path (Home → Manage columns → Choose columns).
  - L3T3S1-1908.png - Task 3: updated "New SQL query" screenshot.
- Lab 4
  - L4T1S1-1908.png, L4T1S3-1908.png - Task 1: updated screenshot references.
  - L4T3S2-1908.png - Task 3: shows the "expand the ribbon menu" note; supports the "Expand lh_FAIAD" / "Then select dbo" wording clarification.
  - L4T4S2-1908.png, L4T4S3-1908.png — Task 4: show the updated Save & Run workflow, including the refresh-tables step.
  - L4T5S7-1908.png - Task 5: screenshot reference update.
  - L4T8S3-1908.png, L4T8S4-1908.png - Task 8: screenshot reference updates.
  - L4T10S11-1908.png - Task 10: shows the "provide access to the Customer table" step, paired with the [IMPORTANT] Customer vs. Customers callout.
- Lab 5
  - L5T1S5-1908.png - Task 1: minor wording update screenshot.
  - L5T1S10-1908.png, L5T1S13-1908.png - Task 1: updated refresh settings step numbering.
  - L5T122-1908.png, L5T1S17-1908.png, L5T1S18-1908.png - Task 1-2: updated pipeline scheduling screenshots.
  - flow-1908.png - Task 5 (NEW): the Until-loop architecture flow diagram introduced before the task steps begin.
  - L5T3S13-1908.png - Task 3: updated screenshot reference.
  - L5T6S6-1908.png, L5T6S14-1908.png - Task 6: variable configuration screenshots, paired with the corrected variable-naming grammar.
  - L5T7S10-1908.png - Task 7: expression builder screenshot.
  - L5T13S3-1908.png, L5T13S11-1908.png - Task 13: pipeline schedule refresh screenshots.
- Lab 6
  - L6T6S25-1908.png, L6T6S30-1908.png - Task 6: new relationship diagram screenshot and updated checkpoint formatting.
  - L6T7S12-1908.png - Task 7: shows the new "expand Measures in Model view" step.
- Lab 7
  - L7T1S7-1908.png, L7T1S12-1908.png, L7T1S12a-1908.png - Task 1: auto-create report and save steps.
  - L7T2S2-1908.png, L7T2S5-1908.png, L7T2S10-1908.png - Task 2: report creation and formatting page steps.
  - L7T3S1-1908.png, L7T3S8-1908.png - Task 3: text box creation step.
  - L7T6S4-1908.png, L7T6S4a-1908.png - Task 6: save steps.
  - L7T8S5-1908.png, L7T8S10-1908.png - Task 8: sort/visual configuration ("Sort axis" → "Sort by").
  - L7T11S4-1908.png, L7T11S6-1908.png, L7T11S19-1908.png - Task 11: shortcut creation process.

### Testing Notes

- Testing Date: 2026-08-19

### Testing Scope
- Review updated instructions and screenshots across Labs 1 through 7.
- Perform end-to-end verification of affected tasks, with particular attention to the new Lab 5 Until-loop flow diagram and task-mapping table, and the Lab 4 Customer vs. Customers table distinction.

</details>


<details>
  <summary>2026-08-03</summary>

## Release Date: 2026-08-03

### Summary of Changes
Updated multiple lab guides to reflect Microsoft Fabric and Power BI UI/workflow updates. Clarified steps for trial activation, SQL query creation, passthrough authentication, pipeline creation, and report image selection. Replaced and renamed screenshots to match the current portal experience.

### Infrastructure Changes
N/A

### Content Changes
- Lab-2.md
  - Step 8: "Select Start trial." → "Select Start trial dropdown and choose Fabric and Power BI."
  - Step 10: "Select Fabric Home Page." → "Select OK."
  - Text updated to reflect Microsoft Fabric and Power BI trial activation flow.

- Lab-3.md
  - Clarified SQL query creation instructions to reference the UI dropdown and "New SQL query" (callouts dropdown (1) and New SQL query (2)).
  - Reused the new SQL query screenshot for multiple query-creation steps.

- Lab-4.md
  - Added explicit auth/connect steps: Select "Passthrough identity" → Click "Connect".
  - Clarified instructions around user authentication for connecting to data sources.

- English/labguide/Lab-5.md
  - Clarified pipeline creation steps and updated pipeline guidance.

- Lab-6.md
  - Clarified SQL query creation instructions and updated query-related text.

- Lab-7.md
  - Clarified file-selection instructions for report background image with explicit path: C:\Users\Public\Desktop\Reports.
  - Instructed to select "Summary Background.png" and click "Open" / "Select".
  - Minor formatting cleanup for "Transparency" wording.

### Screenshot Updates / Filename mapping
- Lab 2
  - image10new-1.png → lab2-trial-fb.png
  - image11.png → lab2-activate.png
  - image12.png → lab2-active-ok.png
  - image14.png → lab2-workspace.png
  - image15.png → lab2-workspace1.png
  - image16.png → lab2-workspace2.png
  - image18.png → lab2-lh.png

- Lab 3
  - image14new.png → lab3-sql-query.png

- Lab 4
  - image38.png → lab4-user-auth.png
  - New: lab4-pass-through.png

- Lab 5
  - image18.png → lab5-new-pipeline.png
  - image26.png → lab5-pipeline.png

- Lab 6
  - image7new.png → lab6-new-sql-query.png

- Lab 7
  - New: lab7-summary-image.png

### Testing Notes
- Testing Date: 2026-08-03
- Verify each renamed screenshot exists in the repository and visually matches the referenced step.
- Validate the Lab-2 trial activation flow in your tenant(s) to confirm the "Start trial dropdown → Fabric and Power BI" wording is accurate across environments.
- Re-run SQL-query creation steps in Labs 3 and 6 to confirm the updated instructions and callouts match the new images.
- Confirm passthrough identity connection in Lab-4 works as documented and lab4-pass-through.png shows the expected UI.
- Confirm Lab-7 background image path and selection behavior in the lab environment.

### Testing Scope
- Review updated instructions and screenshots across Labs 2, 3, 4, 5, 6, and 7.
- Perform end-to-end verification of affected tasks and UI flows described above.

</details>

<details>
  <summary>2026-07-06</summary>

## Release Date: 2026-07-06

### Summary of Changes

- Updated multiple Microsoft Fabric lab guides to align with the latest portal experience.
- Improved learner guidance by refining instructions, updating screenshots, correcting numbering, and documenting newly introduced Microsoft Fabric item types.

### Infrastructure Changes

N/A

### Content Changes

- **Lab 1**
  - Highlighted the **Email** and **Password** fields on the Getting Started page.

- **Lab 2**
  - **Task 1 Step 11:** Added a note instructing learners to navigate back to the **Fabric Home** page.
  - **Task 7 Step 2:** Added an explanation for the **Sample Lakehouse** item type.
  - **Task 9 Step 2:** Added an explanation for the **Azure Databricks Storage** item type.

- **Lab 5**
  - Refined instructions, numbering, formatting, and corrected minor spelling/rendering issues throughout the lab.

### Screenshot Updates

- **Lab 2**
  - **Task 7 Step 2:** Updated the screenshot for the **Sample Lakehouse** item.
  - **Task 9 Step 2:** Updated the screenshot for the **Azure Databricks Storage** item.

- **Lab 4**
  - **Task 4 Step 1:** Replaced the screenshot with corrected numbering.

- **Lab 5**
  - **Task 2 Step 6:** Added a screenshot for the **Run** option in the Microsoft Fabric Pipeline.
  - **Task 13 Step 1:** Added a screenshot demonstrating the **Run** option.

### Testing Notes

- **Testing Date**: 2026-07-06

  Testing activities were carried out on the same date to validate the latest content, screenshots, navigation flow, and Microsoft Fabric UI consistency.

### Testing Scope

- Verified all updated instructions against the latest Microsoft Fabric portal.
- Validated the newly added guidance for **Sample Lakehouse** and **Azure Databricks Storage**.
- Confirmed all updated screenshots align with the corresponding steps.
- Verified screenshot numbering and navigation flow across the affected labs.
- Reviewed formatting, rendering, and instruction clarity throughout the updated content.

</details>

<details>
  <summary>2026-06-17</summary>

## Release Date: 2026-06-17

### Summary of Changes

Updated the lab guide with revised UI screenshots to match the current interface experience. 

### Infrastructure Changes

N/A

### Content Changes

Few screenshots are changed as per the latest test experience. 

### Screenshot Updates

- UI Screenshot in Lab1- Task2- step6
- UI Screenshot in Lab3- Task2- step2
- UI Screenshot in Lab4- Task7- step2
- UI Screenshot in Lab4- Task10- step9
- UI Screenshot in Lab6- Task1- step4
- UI Screenshot in Lab7- Task11- step18

### Testing Notes

- **Testing Date**: 2026-06-17
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>


<details>
  <summary>2026-05-26</summary>

## Release Date: 2026-05-26

### Summary of Changes

Updated the lab guide with revised UI screenshots to match the current interface experience. Instructions across multiple sections were adjusted for better readability and consistency, with improvemen[...]

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**:A few screenshots are changed as per the latest experience and according to screenshots the steps are also refreshed with instructions.

### Testing Notes

- **Testing Date**: 2026-05-26
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-05-06</summary>

## Release Date: 2026-05-06

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and [...]

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency betw[...]

### Testing Notes

- **Testing Date**: 2026-05-06
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-04-10</summary>

## Release Date: 2026-04-10

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and [...]

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency betw[...]

### Testing Notes

- **Testing Date**: 2026-04-10
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-03-27</summary>

## Release Date: 2026-03-27

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and [...]

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency betw[...]

### Testing Notes

- **Testing Date**: 2026-03-27
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-03-19</summary>

## Release Date: 2026-03-19

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and [...]

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency betw[...]

### Testing Notes

- **Testing Date**: 2026-03-19  
  Testing activities were carried out on the same date to validate the content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-02-13</summary>

## Release Date: 2026-02-13

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. instructions were refined to enhance clarity, ensure alignment with the latest interface changes, a[...]

### Infrastructure Changes

N/A

### Content Changes

The content was updated to ensure smoother rendering throughout the guide. Inject keys were added wherever necessary to maintain consistent flow. Additionally, sections related to lakehouse creation a[...]

### Screenshot Updates

- **Minor updates**: Several screenshots were refreshed to reflect the latest UI changes.

### Testing Notes

- **Testing Date**: 2026-02-12  
  All updates were validated on the same day through a detailed review of the revised content, screenshots, and feature behavior.

### Testing Scope 

- Conducted complete end-to-end lab testing. Verified all instructions, user interactions, and flows with the latest UI.  
- Updated the lab guide content and screenshots wherever needed to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-01-20</summary>

## Release Date: 2026-01-20

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and validated.

### Testing Notes

- **Testing Date**: 2026-01-20

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.

</details>

<details>
  <summary>2025-12-26</summary>

## Release Date: 2025-12-26

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-12-26

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.

</details>

<details>
  <summary>2025-12-29</summary>

## Release Date: 2025-12-29

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and validated.

### Testing Notes

- **Testing Date**: 2025-12-29

### Testing Scope 

- Performed end-to-end lab testing and validated.

</details>

<details>
  <summary>2025-12-26</summary>

## Release Date: 2025-12-26

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-12-26

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.

</details>

<details>
  <summary>2025-11-24</summary>

## Release Date: 2025-11-24

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-11-24

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.

</details>

<details>
  <summary>2025-11-03</summary>

## Release Date: 2025-11-03

### Summary of Changes

The lab has been successfully tested without any issues.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

N/A
    
### Testing Notes

- **Testing Date**: 2025-11-03

### Testing Scope 

- Performed end-to-end lab testing, with no issues. We are good with the lab.

---
</details>

<details>
  <summary>2025-10-10</summary>

## Release Date: 2025-10-10

### Summary of Changes

- The lab has been successfully tested, and the lab content has been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-10-10

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.

</details>

<details>
  <summary>2025-09-22</summary>

## Release Date: 2025-09-22

### Summary of Changes

The lab has been successfully tested, and the lab content has been reviewed and updated.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

N/A
    
### Testing Notes

- **Testing Date**: 2025-09-22

### Testing Scope 

- Performed end to end lab testing,with no issues. We are good with the lab.

---
</details>

<details>
  <summary>2025-09-10</summary>

## Release Date: 2025-09-10

### Summary of Changes

The lab has been successfully tested without any issues.   

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

N/A
      
### Testing Notes

- **Testing Date**: 2025-09-10

### Testing Scope 

 Conducted end-to-end testing of the lab successfully.

---
</details>

<details>
  
  <summary>2025-07-29</summary>

### Summary of Changes
No infrastructure changes were made. The lab guide was revised to reflect the latest UI updates, and new screenshots were added accordingly. Testing confirmed that the content is accurate and the lab [...]

### Infrastructure Changes

NA

### Content Changes

Revised the lab guide to incorporate the latest UI changes. 
  
### Screenshot Updates

Updated the lab guide with new screenshots to reflect the latest UI changes.

### Testing Notes

The existing content is good, and the lab is working as expected.

### Testing scope

Validated the complete lab workflow, confirmed the implementation of latest UI updates in instructions and screenshots, and ensured all steps function as expected without impacting existing configurat[...]

</details>

<details>
  
  <summary>2025-07-18</summary>

## Infrastructure Changes

NA

## Content Changes

NA
  
## Screenshot Updates

NA

## Testing Notes

- **Testing Date**: 2025-07-29
- **Resolved Issues**: NA

</details>
<details>
   <summary>April 2025</summary>


- Standardized the color used for image markup to Orange (#F7AC08)

- Updated Power Point to have updated icons

- Updated Instructor Guide demo for Activator to use Teams instead of
  Outlook

- Updated the Solutions folder to include a completed version of the
  advanced pipeline in Lab 05

- Updated following labs:

  - Lab 1:

    - Updated FAIAD.pbix file in the "Reports" directory

    - Cleaned up some state values in the Geo table so they would
      correctly show in the map

    - Updated a few screenshots where the color of the boxes did not use
      the same color

  - Lab 2:

    - Updated screenshots to match the new workloads experience

    - Added a section to the "Overview of Fabric Experiences" to explain
      "Databases"

    - Updated Table of Contents

    - Updated a few screenshots where the color of the boxes did not use
      the same color

  - Lab 3:

    - Updated a few screenshots where the color of the boxes did not use
      the same color

  - Lab 04:

    - Updated a few screenshots where the color of the boxes did not use
      the same color and had some new icons

  - Lab 05:

    - Updated a few screenshots where the color of the boxes did not use
      the same color and had some new icons

    - Added a completed (text file) to the solutions folder for the more
      advanced pipeline

  - Lab 06:

    - Updated a few screenshots where the color of the boxes did not use
      the same color and had some new icons

    - No more **Reporting** tab in Lakehouse so updated the lab
      showcasing how to create new semantic model

  - Lab 07:

    - Updated Screenshots
</details>
<details>
   <summary>February 2025</summary>

- Updated screenshots due to significant changes in the UI, specifically
  with the fabric personas. Labs are updated to point to the workload
  experiences.

- Updated some grammar within the lab documents.

- Updated all labs and instructor guide to reflect latest changes were made as of 02.2025.

- Saved a new PDF version of all labs to make sure the PDF was up to date with the most recent screenshots and lab instructions.
</details>
<details>
   <summary>December 2024 </summary>

- Updated Fabric workspace screenshots for all labs to align with the more recent updates to the UI. All these screenshot updates were to account for UI changes. 

- Updated lab instructions to add specificity due to UI changes. 

- Updated the PDF Documents to include the latest changes were made as of 12.2024 (December) 

- Saved a new PDF version of all labs to make sure the PDF was up to date with most recent screenshots and lab instructions. 
</details>
<details>
   <summary>August 2024</summary>

- Updated following labs:

  - Lab 3:

    - Introduced shortcuts to ingest data from ADLS Gen2 data source.

    - Introduced visual query views to transform data.

  - Lab 4:

    - Introduced shortcuts to another Lakehouse.

  - Lab 6:

    - Introduced creating new semantic model.

  - Lab 7:

    - Introduced the ability to connect Power BI Desktop to semantic
      model.

- Moved Reports and Solutions folder from C:\FAIAD\ folder of lab environment to Desktop.

- Updated all PQT files in the Solutions folder.

- Updated PBIX solution.

- Updated all screenshots.

- Updated pptx slides by including content for Data Mirroring, Linking.

</details>
<details>
   <summary>March 2024</summary>

- Moved Reports and Solutions folder from Desktop of lab environment to C:\FAIAD\ folder.

- Updated all PQT files in the Solutions folder.

- Added PQT file in Solutions folder to connect to Supplier data using
  ADLS Gen2 (to handle scenarios where attendees cannot connect to
  Snowflake)

- Updated PBIX solution:

  - Created missing relationship.

  - Updated ADLS Gen2 queries to reference one main query.

  - Removed May Invoice query. Moved it to the Lab.

- Updated all screenshots.

- Updated labs based on feedback and product update. Here are some of the main updates:

  - Lab 2 - Industry Solutions section is added.

  - Lab 3 - Steps to create ADLS Gen2 base folder are updated.

  - Lab 3 and 4 - Steps to copy and paste queries to Dataflow are
    updated.

  - Lab 6 - T-SQL and Visual query section are updated to reflect
    changes in the product.

  - Lab 6 - Create relationships and measures section is updated to
    reflect changes in the product.

  - Lab 7 -- Auto-create report section is updated to reflect how the
    report may look if optional relationships are created vs only the
    required relationships are created.

- Updated instructor guide by adding links to labs (language specific links).

- New demo added for Data Activator. Demo steps added to Instructor guide.
</details>







