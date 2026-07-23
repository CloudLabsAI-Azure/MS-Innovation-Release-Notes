# AI-Assisted Development with GitHub Copilot

Welcome to the **AI-Assisted Development with GitHub Copilot** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, bug fixes, and other relevant changes for the lab.

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
<summary>2026-07-20</summary>
 
## Release Date: 2026-07-20
 
### Summary of Changes

Updated the lab documentation by adding new validation steps and refreshing screenshots to align with the current Visual Studio Code and Microsoft Foundry experience.
 
### Infrastructure Changes

New Validations are added:

- Exercise 1: Introduction to GitHub Copilot > Task 3: Project Initialization and Requirements

- Exercise 4: DevOps with GitHub CoPilot – Azure Deployment via Prompts > Task 2: Deploy and Validate Application

- Exercise 4: DevOps with GitHub CoPilot – Azure Deployment via Prompts > Task 4: Introduce GitHub CoPilot Custom Chat Instructions
 
### Content Changes

- gettingstarted.md

  - Added a Copilot pop-up note and supporting screenshot advising learners to close the “Start using Copilot” pop-up when it appears.
  - Small heading/copy adjustments (e.g., "Lab Overview", "Prerequisites").

- Exercise01.md

  - Task 3 (Project initialization / clone): Updated example fork URL and Owner name used in instructions (repository name injection example changed).
  - Replaced several fork/clone/sign-in screenshots to match current VS Code/GitHub screens.
  - Added a "Congratulations" / validation guidance block after the cloning steps.
  - Task 4 (Discover Copilot Tools): Clarified sign-in guidance and ensured the step text matches current VS Code behavior (no screenshot changes for Task 4 in this PR).

- Exercise02.md

  - Updated left-navigation instruction wording from “Models” → “Deployments”.
  - Replaced Foundry-related screenshots to reflect the Deployments view and wording.

- Exercise04.md

  - Adjusted validation block (validation step ID updated).
  - Fixed a minor typographical issue.

- Exercise05.md

  - Removed/repositioned a legacy validation block and adjusted summary placement.
  - Minor copy edits across files for clarity and consistency (headings, notes, and small wording fixes).

### Screenshot Updates

- media/clf.png Replaces media/2026-04-24_01.png in Exercise01 Task 3 (fork / Copy link step).

- media/cnf.png Replaces media/E1T3S2-1501.png in Exercise01 Task 3 (Create a new fork dialog — Owner/Repository name).

- media/url.png Replaces media/E1T3S3-1501.png in Exercise01 Task 3 (forked repo main page / copy URL).

- media/tsb.png Replaces media/ex1-task3--4.png in Exercise01 Task 3 (VS Code clone/search bar screenshot).

- media/gasi.png Replaces media/ex1-task3--2.png in Exercise01 Task 3 (VS Code GitHub sign-in / authorize flow).

- media/deploy.png Replaces media/2026-04-24_08-n1.png in Exercise02 (Foundry left-nav; instruction updated from “Models” → “Deployments”).

- media/pop.png New screenshot added to gettingstarted.md showing the Copilot “Start using Copilot” pop-up (guidance: close it).

### Testing Notes
 
- **Testing Date**: 2026-07-20

### Testing Scope

 Validation performed by running end-to-end walkthroughs of the updated lab content in the lab VM environment and verifying the updated screenshots, copy, and validation guidance.

 
</details>

<details>
<summary>2026-07-07</summary>
 
## Release Date: 2026-07-07
 
### Summary of Changes
 
Updated the lab to support the latest Microsoft Foundry experience by replacing Azure OpenAI references, aligning the content with the latest Visual Studio Code UI, enhancing user guidance, and refreshing screenshots to accurately reflect the current workflow and portal experience.
 
### Infrastructure Changes
 
- Replaced the Azure OpenAI resource with Microsoft Foundry since the Azure OpenAI does not support new foundry portal experience.
 
### Content Changes

* Added a **Resize the virtual machine view** section to the **Getting Started** page to improve the overall user experience.
* **Exercise 1, Task 3, Steps 5 and 11; Task 4, Step 1** – Updated the instructions and note to align with the latest **Visual Studio Code** UI and improved content clarity.
* **Exercise 2, Task 2, Steps 2, 6–11** – Replaced references to **Azure OpenAI** with **Microsoft Foundry**.
* **Exercise 4, Task 1, Step 10** – Corrected a typographical error.
* **Exercise 4, Task 2, Step 1; Task 3, Step 2; Exercise 7, Task 2, Step 5** – Updated the instructions for launching a new terminal to align with the latest **Visual Studio Code** experience.

### Screenshot Updates

* Added a screenshot for the **Resize the virtual machine view** section on the **Getting Started** page.
* **Exercise 1, Task 3, Step 5; Task 4, Steps 1–2** – Updated screenshots to align with the latest **Visual Studio Code** UI and improve clarity.
* **Exercise 2, Task 1, Steps 2 and 13; Task 2, Steps 2, 6–11; Task 3** – Updated screenshots to reflect the latest **Visual Studio Code** UI and replaced **Azure OpenAI** with **Microsoft Foundry** where applicable.
* **Exercise 3, Task 1, Step 1; Task 2, Step 1; Task 3, Step 1** – Updated screenshots to align with the latest **Visual Studio Code** UI.
* **Exercise 4, Task 1, Steps 1, 8, and 10; Task 2, Step 1; Task 3, Step 2** – Updated screenshots to reflect the latest **Visual Studio Code** UI, GitHub repository view, and **Environment** tab.
* **Exercise 5, Task 1, Step 10; Task 2, Steps 11 and 14** – Updated screenshots to align with the latest **Visual Studio Code** UI and lab workflow.
* **Exercise 6, Task 1, Steps 21, 24, and 26; Task 2, Step 2** – Updated screenshots to align with the latest **Visual Studio Code** UI.
* **Exercise 7, Task 1, Step 6; Task 2, Step 5** – Updated screenshots to align with the latest **Visual Studio Code** UI.
 
### Testing Notes
 
- **Testing Date**: 2026-07-07

### Testing Scope
 
- Validated the updated Microsoft Foundry workflow, including the revised lab instructions, Visual Studio Code UI changes, terminal launch workflow, and the replacement of Azure OpenAI references with Microsoft Foundry. Verified that the updated content and screenshots accurately reflect the latest portal experience and function correctly during end-to-end testing.
 
</details>

<details>
<summary>2026-06-16</summary>
 
## Release Date: 2026-06-16
 
### Summary of Changes
 
Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners.
 
### Infrastructure Changes
 
N/A
 
### Content Changes

- Updated outdated GitHub Copilot UI screenshots.
- Corrected step numbering and step references in multiple sections.
- Added instructional notes to provide better guidance and improve learner experience.
- Blurred unique IDs, environment-specific values, and sensitive information where applicable.

### Screenshot Updates
 
- Refreshed multiple screenshots to reflect the latest GitHub Copilot UI and workflow.
- Updated screenshots containing outdated interfaces and environment-specific information.
- Ensured screenshots are aligned with the latest instructions and learner experience.
 
### Testing Notes
 
- **Testing Date**: 2026-06-16
 
### Testing Scope
 
- Performed complete end-to-end lab testing. Verified all instructions, interactions, and user flows with the latest UI.
 
</details>

<details>
<summary>2026-06-01</summary>
 
## Release Date: 2026-06-01
 
### Summary of Changes
 
Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners.
 
### Infrastructure Changes
 
N/A
 
### Content Changes
- Lab Scenario added in whole guide.
- Page2 - Exercise1 - Task4 -Enable Inline Suggestions screenshots and instruction is changed.
- Page7 - Exercise6 - Task1 -Point n0.21 screnshot changed.
- Next page indicating screenshot changed in whole lab.
### Screenshot Updates
 
- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency between steps and images.
 
### Testing Notes
 
- **Testing Date**: 2026-06-01
  Testing activities were carried out on the same date to validate the content, screenshots, and feature behavior.
 
### Testing Scope
 
- Performed complete end-to-end lab testing. Verified all instructions, interactions, and user flows with the latest UI.
 
</details>

<details>
  <summary>2026-05-28</summary>

## Release Date: 2026-05-28

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners. Step-level guidance has been improved in multiple tasks to reduce ambiguity and ensure smoother navigation during the lab.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency between steps and images.

### Testing Notes

- **Testing Date**: 2026-05-28
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
<summary>2026-04-14</summary>
 
## Release Date: 2026-04-14
 
### Summary of Changes
 
Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners.
 
### Infrastructure Changes
 
N/A
 
### Content Changes

* **Exercise 01 – Task 4 – Step 10:** Updated screenshot for the model selection UI.
* **Exercise 01 – Task 4 – Step 10:** Updated screenshot for the “Add Context” option in VS Code.
* **Exercise 04 – Task 4 – Step 1:** Updated the screenshot to include step annotations.
* **Exercise 04 – Task 4 – Step 2:** Added a screenshot for the new “Generate agent instructions” option.
* **Exercise 05 – Task 2 – Step 2:** Updated the screenshot to include step annotations.

### Screenshot Updates
 
- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency between steps and images.
 
### Testing Notes
 
- **Testing Date**: 2026-04-14
  Testing activities were carried out on the same date to validate the content, screenshots, and feature behavior.
 
### Testing Scope
 
- Performed complete end-to-end lab testing. Verified all instructions, interactions, and user flows with the latest UI.
 
</details>

<details>
  <summary>2026-03-23</summary>

## Release Date: 2026-03-23

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners. Step-level guidance has been improved in multiple tasks to reduce ambiguity and ensure smoother navigation during the lab.

### Infrastructure Changes

N/A

### Content Changes

* Screen 1 (Login to GitHub), Step 4: Sign-in steps have been added to the screenshot.
* Exercise 1 – Task 3, Step 5: Updated with the new GitHub UI screenshot and revised text.
* Exercise 1 – Task 4 (Use Agent Mode): Step numbering corrected as per the screenshot.
* Exercise 1 – Task 4 (Other Available Features), Step 1: Text updated to match the current UI.
* Exercise 1 – Task 4 (Other Available Features), Step 4.3: Added in both screenshot and text for better clarity.
* Exercise 2 – Task 1, Step 1: Copilot icon text updated to “Toggle Chat” to align with the current UI.
* Exercise 2 – Task 1, Step 10: Added a screenshot to enhance user experience.
* Exercise 2 – Task 2, Step 4: Added clear guidance to use Microsoft Edge for opening the Azure portal.
* Exercise 2 – Task 2, Step 6: Updated Copilot icon text as per the current UI.
* Exercise 4 – Task 1, Step 12: Added guidance to use Microsoft Edge for opening the Azure portal.
* Exercise 4 – Task 3, Step 7: Sensitive lab details have been blurred in the screenshot.
* Exercise 4 – Task 4, Step 1: Added clear instruction to navigate to the chat section and click the gear icon.
* Exercises 5, 6, 7: Updated Copilot icon text across all steps to match the current UI.

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency between steps and images.

### Testing Notes

- **Testing Date**: 2026-03-23
  Testing activities were carried out on the same date to validate the content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>

<details>
  <summary>2026-02-27</summary>
  
## Release Date: 2026-02-27

### Summary of Changes

Performed end-to-end lab testing and validations, with no major content and screenshots update.

### Infrastructure Changes

N/A

### Content Changes

Updated content for better clarity.

### Screenshot Updates

Screenshots were good as per the latest UI.

## Validations

Validations are good.

### Testing Notes

- **Testing Date**: 2026-02-27

### Testing Scope 

Successfully completed end-to-end lab testing and validation. Thoroughly reviewed and validated all lab instructions and screenshots, ensuring they are accurate, up to date, and aligned with the latest UI changes. 

---
</details>

<details>
  <summary>2026-02-04</summary>
  
## Release Date: 2026-02-04

### Summary of Changes

Performed end-to-end lab testing and validations, with no major content and screenshots update.

### Infrastructure Changes

N/A

### Content Changes

Updated content for better clarity.

### Screenshot Updates

Screenshots were good as per the latest UI.

## Validations

Validations are good.

### Testing Notes

- **Testing Date**: 2026-02-04

### Testing Scope 

Successfully completed end-to-end lab testing and validation. Thoroughly reviewed and validated all lab instructions and screenshots, ensuring they are accurate, up to date, and aligned with the latest UI changes. 

---
</details>

<details>
  <summary>2026-01-22</summary>

## Release Date: 2026-01-22

### Summary of Changes

N/A

### Infrastructure Changes

N/A

### Content Changes
N/A 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: N/A. 

### Testing Notes

- **Testing Date**: 2026-01-22

### Testing Scope 

Performed end-to-end validation and prerequisite verification.

---
</details>

<details>
  <summary>2026-01-16</summary>

## Release Date: 2026-01-16

### Summary of Changes

Added clear screenshots and enhanced instructions.  

### Infrastructure Changes

N/A

### Content Changes
N/A 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: A few of the images were not clear, hence replaced them with clearer ones. 

### Testing Notes

- **Testing Date**: 2026-01-15

### Testing Scope 

Performed end-to-end lab testing and validations, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-12-31</summary>

## Release Date: 2025-12-31

### Summary of Changes

- Performed end to end lab testing, and all validations were successful. Updated lab guide for better clarity.  

### Infrastructure Changes

N/A

### Screenshot Updates

- **Minor updates**: 

N/A

### Testing Notes

- **Testing Date**: 2025-12-31

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully.

---
</details>

<details>
  <summary>2025-12-12</summary>

## Release Date: 2025-12-12

### Summary of Changes

Made updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity.  

### Infrastructure Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated screenshots as per the new UI. 

### Testing Notes

- **Testing Date**: 2025-12-12

### Testing Scope 

Performed end-to-end lab testing and validations, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-11-25</summary>

## Release Date: 2025-11-25

### Summary of Changes

Made updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity.  

### Infrastructure Changes

N/A

### Content Changes

- Instructions updated as per UI updates in Microsoft Foundry Portal. 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated screenshots as per the new UI. 

### Testing Notes

- **Testing Date**: 2025-11-25

### Testing Scope 

Performed end-to-end lab testing and validations, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-11-17</summary>

## Release Date: 2025-11-17

The internal testing is currently in progress, and the final pointers will be updated upon its completion.

</details>

<details>
  <summary>2025-10-21</summary>

## Release Date: 2025-10-21

### Summary of Changes

Updated the lab guide with minor screenshot changes for UI updates.

### Infrastructure Changes

N/A

### Content Changes

Instructions were updated to be clearer.

### Screenshot Updates

Screenshots were updated to enhance the overall user experience.

## Validations

Validations are good.

### Testing Notes

- **Testing Date**: 2025-10-21

### Testing Scope 

  Conducted end-to-end testing, RBAC/policy checks, prerequisite checks, validated the lab guide steps, and enhanced the lab guide with new latest screenshots.

---
</details>

<details>
  <summary>2025-09-26</summary>

## Release Date: 2025-09-26

### Summary of Changes

Validations updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.

### Infrastructure Changes

N/A

### Content Changes

Instructions were updated to be more precise and clear.

### Screenshot Updates

Screenshots were updated to enhance the overall user experience.

## Validations

Validations are updated and good.

### Testing Notes

- **Testing Date**: 2025-09-26

### Testing Scope 

  - End-to-end validation
  - Role-Based Access Control (RBAC) checks
  - Policy verification
  - Prerequisite validation

---
</details>







