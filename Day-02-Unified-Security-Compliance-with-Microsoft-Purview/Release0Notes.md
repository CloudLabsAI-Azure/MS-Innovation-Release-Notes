# Day 02: Unified Security & Compliance with Microsoft Purview

Welcome to the **Day 02: Unified Security & Compliance with Microsoft Purview** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com

# Release Notes

<details>
  <summary>2026-11-18</summary>

## Release Date: 2026-11-18

### Summary of Changes

Updated the Microsoft Purview lab guide with clearer instructions, corrected task sequencing, additional troubleshooting guidance, and refreshed screenshots. Changes cover Getting Started and Exercises 00–06, including sensitivity labels, SharePoint, information protection, mail encryption, and DLP workflows.

### Content Changes

- **Getting Started**
  - Corrected and clarified the lab environment, credentials, and portal guidance.
  - Updated the Environment tab and Split Window instructions to match the screenshots and interface.

- **Exercise 00 – Prerequisites**
  - **Purview role setup:** Clarified the role-group assignment instructions and permission-propagation note.
  - Updated the listed role groups to assign, including **Content Explorer Content Viewer** and **Content Explorer List Viewer**.
  - Corrected spelling and wording in the completion instructions.

- **Exercise 01 – Configure and Publish Sensitivity Labels**
  - **Task 1:** Clarified the SharePoint PowerShell module installation and tenant-name instructions.
  - **Tasks 1 and 2:** Clarified which protection settings to select and that all other checkboxes should remain unchecked.
  - Added and updated guidance for creating and editing sensitivity labels, reviewing label publishing policies, and verifying label availability in Microsoft 365 apps.
  - Added a note explaining that if auditing is already enabled, learners may see an auditing banner instead of the **Turn on auditing** button and can proceed without enabling it again.
  - Corrected wording around Microsoft-created labels and the labels learners should use.

- **Exercise 02 – Configure Message Encryption and Protection**
  - **Task 1:** Added a screenshot after completing the mail-flow rule setup.
  - Clarified the description of the **Do Not Forward** template and the protection it applies.
  - **Task 2:** Updated the Outlook navigation screenshot and clarified the wait guidance for the **Set permissions on this item** option.

- **Exercise 03 – Install and Use the Microsoft Purview Information Protection Client**
  - **Task 1:** Updated the download screenshot and clarified the installation and Office integration instructions.
  - **Task 2:** Corrected the sensitivity-label instructions and added a screenshot showing the completed operation.
  - Clarified the guidance for applying labels through File Explorer and Office apps.
  - Refined the note about checking a file’s protection status.

- **Exercise 04 – Advanced Sensitivity Label Scenarios**
  - **Task 1:** Refreshed SharePoint and Microsoft 365 admin center screenshots and clarified the steps for creating labeled groups and sites.
  - **Task 2:** Updated the test-user license, password-reset, and sign-in instructions.
  - Clarified how **Internal** and **Confidential** labels affect a user’s ability to access a document.
  - **Reporting and exploration:** Refreshed the screenshots and corrected guidance for reviewing label analytics, Content Explorer, and Activity Explorer.
  - Clarified that reporting data may be limited or unavailable immediately in a newly configured lab environment.

- **Exercise 05 – Create a Data Loss Prevention (DLP) Policy**
  - Updated the task order so learners assign the required Microsoft Purview role groups **before** creating the DLP alert policy.
  - **Task 1:** Refreshed screenshots and clarified the policy conditions, sensitive information types, actions, and user notification settings.
  - **Task 2:** Added steps to assign the user to **Security Administrator**, **Audit Manager**, **Organization Management**, **Compliance Administrator**, and **Purview Administrators**.
  - Added steps to verify membership in all five role groups and guidance for permission propagation, signing out and back in, and waiting for changes to take effect.
  - **Task 3:** Added troubleshooting instructions for when **+ New Alert Policy** is missing, including a direct link to the alert-policies page.
  - **Task 4:** Clarified the email simulation instructions and the expected delay before DLP alerts appear.

- **Exercise 06 – Configure and Investigate Data Loss Prevention Alerts**
  - Clarified the note about waiting for DLP alerts to appear after a policy violation.
  - Refreshed the DLP reports and Activity Explorer screenshots.
  - Corrected the descriptions of the DLP reports to make clear what each report shows.

### Screenshot Updates

- **Getting Started**
  - Added `envnew.png` to show the latest lab Environment tab.
  - Added `split.png` to demonstrate the Split Window feature.
  - Updated the lab environment instructions to match both screenshots.

- **Exercise 00 – Prerequisites**
  - Updated the Office 365 Apps download screenshots.
  - Refreshed Purview role-group screenshots.
  - Updated `np2.png`, used on the prerequisites completion page.

- **Exercise 01 – Configure and Publish Sensitivity Labels**
  - Added `envnew1.png` to show the tenant name in the Environment tab.
  - Added `sol.png` to show the latest Information Protection navigation.
  - Added `sol2new.png` to show the Sensitivity labels page.
  - Added `sol3.png` to show label editing options.
  - Added `sol5.png` to show the label completion page.
  - Added `sol6.png` to show the **Highly Confidential** label workflow.
  - Added `sol9.png` to show the label publishing policy.
  - Refreshed screenshots for Word, Excel, PowerPoint, Outlook, and Teams.
  - Updated the final exercise navigation screenshot.

- **Exercise 02 – Configure Message Encryption and Protection**
  - Added `EM1.png` to show the Exchange mail-flow rule navigation.
  - Added `v40new.png` to show the completed mail-flow rule configuration.
  - Updated Outlook navigation to `v11i.png`.
  - Updated screenshots related to encrypted email creation and permissions.

- **Exercise 03 – Install and Use the Microsoft Purview Information Protection Client**
  - Updated `ig15n.png` to show the latest Purview Information Protection client download.
  - Added `e4new.png` to show the completed protection operation.
  - Added `e8new.png` to show the sensitivity-label application result.
  - Updated the Word launch screenshot to `v7i.png`.
  - Updated the PowerPoint launch screenshot to `v8i.png`.
  - Updated the final exercise navigation screenshot.

- **Exercise 04 – Advanced Sensitivity Label Scenarios**
  - Updated `v12i.png` to show the latest Microsoft 365 Admin navigation.
  - Added `v1new.png` for creating a Microsoft 365 group.
  - Added `i54new.png` for assigning a group owner.
  - Added `e38new.png` to show the newly created **Internal-LabelTest** group.
  - Added `e39new.png` to show the **View Site** option for the Internal test site.
  - Added `e43new.png` to show the **View Site** option for the Confidential test site.
  - Added `e412.png` to show the test-user license and account details.
  - Added `ex13.png` to show the test-user password-reset page.
  - Added `e415.png` to show SharePoint navigation.
  - Added `ex4x3.png` to show Information Protection navigation.
  - Added `ex434.png` to show the Reports page.
  - Added `e491.png` to show the label analytics dashboard.
  - Added `e433.png` to show label coverage and the **Explore label items** option.
  - Added `e434.png` through `e443.png` to show sensitivity-label exploration, SharePoint locations, Content Explorer folders, file details, and reporting views.
  - Added `e486.png` through `e489.png` to show Activity Explorer navigation and activity details.
  - Updated the final exercise navigation screenshot.

- **Exercise 05 – Create a Data Loss Prevention (DLP) Policy**
  - Added `cc6new.png` to show the DLP **Content contains** condition.
  - Added `cc8new.png` to show the DLP action menu.
  - Refreshed role-assignment screenshots for the five required role groups.
  - Added `ETS533.png` to show the updated completed role-member selection.
  - Added `L6.png` to show the Microsoft Defender **Alert Policy** page and **+ New Alert Policy** option.
  - Updated `open.png` to show opening Outlook from the app launcher.
  - Updated DLP testing screenshots and the alert-monitoring workflow.
  - Updated the final exercise navigation screenshot.

- **Exercise 06 – Configure and Investigate Data Loss Prevention Alerts**
  - Replaced ETS611.png with vnew.png to show the updated DLP reports dashboard.
  - Replaced e4x84.png with e484.png to show how to open Activity Explorer.
  - Replaced e4x85.png with e485.png to show the DLP activity data and support investigation of policy matches and user activity.

### Testing Notes

- **Testing Date:** 2026-11-18

### Testing Scope

 Reviewed the lab guide end-to-end after the changes.
- Verified the revised task sequence and instructions.
- Confirmed that role-group assignments occur before alert-policy creation.
- Reviewed role-member verification and permission-propagation guidance.
- Tested troubleshooting for the missing **+ New Alert Policy** button.
- Reviewed the updated SharePoint, sensitivity-label, DLP, and alert workflows.
- Compared screenshots with the corresponding instructions.
- Checked formatting, copy-paste text, and links.

</details>

<details>
  <summary>2026-08-12</summary>

## Release Date: 2026-08-12

### Summary of Changes

Updated the Microsoft Purview lab guide across Exercises 00–06 to align with the latest portal UI, workflows, screenshots, and observed lab behavior. Refined instructions throughout the lab and added notes for known UI delays and expected-output scenarios.

### Content Changes

- **Getting Started**
  - Added the lab scenario.
  - Added icons for the section headings.
  - Updated the Lab VM instructions and supporting images.

- **Exercise 00**
  - **Task 1, Step 1:** Updated the Microsoft 365 Apps download link and screenshots.
  - **Task 2, Step 3:** Updated the Microsoft Purview portal instructions and screenshot based on the latest UI.
  - **Task 2, Step 9 onward:** Updated the role-assignment flow, instructions, and screenshots according to the latest workflow.

- **Exercise 01**
  - **Task 1, Step 4:** Updated the screenshot with the latest Environment tab.
  - **Task 3, Step 9:** Updated the screenshot with the latest Admin Center icon/UI.
  - **Task 4, Step 22:** Added a note explaining that the Download option may appear greyed out.

- **Exercise 02**
  - Highlighted relevant keywords in the instructions to improve learner guidance.

- **Exercise 03**
  - **Task 1, Step 2:** Updated the screenshot to clearly identify the software to download.
  - **Task 1, Step 10:** Added an instruction to create/add a blank Word document.
  - **Task 1, Step 14:** Added sign-in guidance when prompted for credentials.
  - **Task 2, Step 3:** Added a note for cases where sensitivity labels are not immediately displayed.
  - **Task 2, Step 21:** Added a note for cases where Protection status is not immediately displayed.
  - **Task 2, Step 25:** Added a note for cases where Protection details are not immediately available.

- **Exercise 04**
  - **Task 1, Step 1:** Updated the screenshot with the latest icons.
  - **Task 1:** Refreshed multiple screenshots with the latest SharePoint UI and refined the instructions.
  - **Task 1, Step 38:** Added a note for cases where the Confidential label is not immediately available when moving the file between SharePoint sites.
  - **Task 2, Step 20:** Added an updated screenshot and instructions for the test user sign-in flow to the Purview portal.
  - **Task 2:** Refreshed multiple screenshots with the latest SharePoint UI and improved the instructions.
  - **Task 2, Step 28:** Added a note for cases where the document opens even though access is expected to be restricted.

- **Exercise 05**
  - **Task 3:** Updated the role-assignment flow, screenshots, and instructions according to the latest workflow.

- **Exercise 06**
  - **Task 1, Step 4:** Updated the instructions based on the latest portal options.
  - **Task 3, Step 3:** Corrected the Inject Key instruction to use the Azure email ID instead of the password.
  - **Task 4, Step 2:** Updated the option from **Posture Report** to **Report** based on the current portal UI and screenshot.

  - Refined instructions and improved learner guidance across all exercises.

### Screenshot Updates

- Updated screenshots across Exercises 00–06 to reflect the latest Microsoft Purview, Microsoft 365, SharePoint, and Admin Center UI.
- Updated screenshots for revised workflows, portal options, icons, role assignments, software downloads, and SharePoint experiences.
- Masked sensitive email information in screenshots where required.
- Improved screenshots and visual guidance throughout the lab.

### Testing Notes

- **Testing Date:** 2026-08-12

### Testing Scope

- Reviewed the updated lab guide across all the exercises.
- Verified the updated tasks and steps are in the correct sequence.
- Validated instructions against the latest portal UI and observed lab workflows.
- Reviewed the updated screenshots for alignment with the corresponding instructions.
- Refined the  instructions and added notes to provide guidance for these scenarios.

</details>

<details>
  <summary>2026-03-10</summary>

## Release Date: 

### Summary of Changes

### Content Changes

### Screenshot Updates
      
### Testing Notes

- **Testing Date**: 

### Testing Scope 

---
</details>
