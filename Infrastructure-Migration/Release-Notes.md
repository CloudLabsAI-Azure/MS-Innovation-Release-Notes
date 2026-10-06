
#  Infrastructure Migration

Welcome to the **Infrastructure Migration** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>

<summary>2026-10-06</summary>

## Release Date: 2026-10-06

### Summary of Changes

- Updated the Infrastructure Migration lab guide across the Getting Started section, HOL1, HOL2, HOL3, and Business Case exercises to align with the latest UI, lab flow, and learner experience.
- Added and updated scenarios throughout the lab to provide a consistent SmartHotel storyline and better context for each hands-on exercise.
- Refreshed screenshots and instructions across the lab to reflect the latest portal experience and updated workflows.
- Removed Azure Automanage content as the service has been retired and the related tasks were no longer functional.
- Added new steps for VMSS deployment verification and Microsoft Entra ID (SSO) sign-in for the Red Hat Linux VM.
- Reviewed and updated exercise durations to better reflect the current lab content.
- Improved overall learner guidance, readability, and consistency across the lab.

### Infrastructure Changes

- N/A

### Content Changes

**Getting Started**
- Added an updated architecture diagram.
- Refined the objectives, prerequisites, and component descriptions.
- Updated the workshop scenario and added an overview of the HOLs.
- Added updated Environment tab and split-screen screenshots reflecting the latest UI.

**HOL1 – Exercise 1**
- Added a link in Task 1 – Step 16 for validation.
- Added screenshots for refreshing the appliance in Step 20 and using another account in Step 24.
- Added a note in Step 29 instructing learners not to enter spaces in the FQDN.
- Added the required SQL Authentication and MySQL Server login credential steps to support successful discovery.

**HOL1 – Exercise 2**
- Updated assessment creation screenshots in Task 1 to reflect the latest UI.
- Added steps in Task 2 – Steps 1 and 2 to log in to `smarthotelhost` through Hyper-V.
- Removed the failing validations.

**HOL1 – Exercise 3**
- Updated the Test Migration, Cleanup, and Migration screenshots in Tasks 3, 4, and 5 based on the latest workflow.
- Refined instructions for better clarity.
- Removed the Task 2 validation.
- Added relevant scenario-based guidance.

**HOL1 – Exercise 4**
- Added steps to open the Virtual Machine Scale Set after deployment and verify that the instances are running.

**HOL2 – Exercise 3**
- Added an updated screenshot for Task 4 showing the server migration flow using the latest UI.
- Added steps to complete Microsoft Entra ID sign-in for the Red Hat Linux VM after installing the SSH login extension:
  - Verify the extension.
  - Assign the **Virtual Machine Administrator Login** role.
  - Connect through **Azure Bastion** using Microsoft Entra ID authentication.
  - Confirm the signed-in user.

**HOL3 – Exercise 1**
- Added a screenshot demonstrating PowerShell script execution.
- Added a note instructing learners to verify the PowerShell script output before proceeding.

**Business Case Exercise**
- Added objectives to clearly define the expected learning outcomes.
- Replaced the existing business case screenshot with an updated screenshot showcasing the new workloads.

**Azure Automanage Removal**
- Removed Azure Automanage tasks and related content from HOL1 and HOL2 because the service has been retired and the tasks were no longer functional.

- Overall refined the instructions throughout the lab guide.

**### Screenshot Updates**

- Added and refreshed screenshots across the Getting Started section and HOL1, HOL2, HOL3, and Business Case exercises.
- Updated screenshots to reflect the latest Azure portal and lab UI.
- Added screenshots for appliance refresh, alternate account usage, assessment creation, server migration, PowerShell execution, Test Migration, Cleanup, Migration, VMSS deployment verification, and other updated workflows.
- Updated the architecture diagram and business case visuals.
- Added relevant screenshots wherever new steps or scenarios were introduced.

**### Testing Notes**

- **Testing Date**: 2026-10-06

**### Testing Scope**

- Performed validation of the updated lab guide and reviewed the end-to-end flow across the updated exercises.
- Verified that the updated instructions, screenshots, scenarios, and workflows align with the current lab experience.
- Reviewed the updated validation logic and removed validations that were failing or no longer applicable.
- Verified the updated VMSS deployment check and Microsoft Entra ID authentication flow for the Red Hat Linux VM.
- Confirmed that the retired Azure Automanage content has been removed from the applicable exercises.

</details>

<details>
  <summary>2026-06-30</summary>

## Release Date: 2026-06-30

### Summary of Changes

- Updated the lab guide to align with the latest Azure Migrate portal experience. Revised the instructions across all exercises, refreshed outdated screenshots, and added new screenshots to accurately reflect the current Azure migration workflow and portal navigation.

### Infrastructure Changes

- N/A

### Content Changes

- Updated the lab guide to align with the latest Azure Migrate UI.
- Revised the instructions for agentless dependency analysis based on the current Azure Migrate workflow.

### Screenshot Updates

- Updated screenshots across all exercises to align with the latest Azure Migrate portal UI.
- Added new screenshots where required to reflect the updated workflow.

### Testing Notes

- **Testing Date**: 2026-06-30

### Testing Scope

- Performed end-to-end validation of the lab. Verified that the Azure Migrate workflow aligns with the current Azure portal experience.

</details>

<details>
  <summary>2026-06-09</summary>

## Release Date: 2026-06-09

### Summary of Changes

* Updated the AIW-Infra-Migration lab guide to align with the latest Azure Migrate portal experience. Revised instructions across Module 1, Module 2, and HOL3 exercises, refreshed outdated screenshots, and added new screenshots to accurately reflect the current Azure migration workflow and portal navigation.

### Infrastructure Changes

* NA

### Content Changes

* Updated Module 1 Exercise 1–4 instructions to reflect current Azure Migrate workflows.
* Updated Module 2 Exercise 1–4 instructions to align with the latest Azure portal experience.
* Updated HOL3 Exercise 1–5 guidance and navigation steps.
* Improved instructional clarity and accuracy across migration-related tasks.
* Revised learner guidance to match the current Azure portal layout and migration process.

### Screenshot Updates

* Refreshed and updated the existing screenshots to ensure alignment with the latest Azure Portal user interface across Module 1 (Exercises 1–4), Module 2 (Exercises 1–4), and the corresponding Hands-on Labs (HOLs).


### Testing Notes

* **Testing Date**: 2026-06-09

### Testing Scope

* Performed end-to-end validation of the AIW-Infra-Migration lab.
* Verified all updated Module 1, Module 2, and HOL3 instructions.
* Confirmed Azure Migrate workflow steps match the current Azure portal experience.
* Validated newly added and updated screenshots for accuracy and consistency.
* Reviewed lab flow, navigation, and content formatting to ensure a seamless learner experience.

</details>

<details>
  <summary>2026-05-19</summary>

## Release Date: 2026-05-19

### Summary of Changes 

- Added detailed lab scenarios to simulate real-world Azure migration and hybrid infrastructure management workflows, included additional guidance notes to help users proactively handle common issues during execution, and corrected content formatting, rendering inconsistencies, and grammatical errors throughout the lab guide.

### Infrastructure Changes

- NA

### Content Changes

- Updated the lab guide to include realistic, role-based scenarios that align with enterprise Azure migration and hybrid cloud management use cases.
- In E1, T1, S25 - Included additional guidance notes to help users identify, troubleshoot, and resolve common issues encountered during lab execution.
- HOL 3: E2, T3, S2 - Added a guidance note to assist users in troubleshooting scenarios where the Log Analytics workspace is not displayed or configured correctly during the lab execution.

### Screenshot Update

- HOL 3: E2, T3, S2 - Added an additional screenshot to provide clearer navigation guidance and help users easily locate the required options and settings within the lab environment.

### Testing Notes

- **Testing Date**: 2026-05-19

### Testing Scope 

- Performed comprehensive validation of the lab environment, refined RBAC and policy configurations, refreshed outdated screenshots, and improved procedural guidance to enhance usability, accuracy, and overall learner experience.


</details>

<details>
  <summary>2026-03-02</summary>

## Release Date: 2026-03-02

### Summary of Changes 

- Successfully validated the lab workflow to ensure all steps function as expected and align with the intended learning objectives, incorporating the updated lab VM image and the latest Azure Migrate UI updates.

### Infrastructure Changes

- Updated the deployment script and VM image, refined RBAC configurations, and validated successful VM provisioning and replication over multiple regions.

### Content Changes

- Updated the lab guide to ensure consistency in the UI experience and improve overall clarity.

### Screenshot Update

- Revised several screenshots by masking subscription IDs, resource names, and region details to maintain security and compliance standards.

### Testing Notes

- **Testing Date**: 2026-03-02

### Testing Scope 

- Conducted testing, RBAC/policy, updated screenshots, and enhanced the instructions for clarity.

</details>

<details>
  <summary>2026-01-02</summary>

## Release Date: 2065-01-02

### Summary of Changes 

- Screenshots and instructions updates.

### Infrastructure Changes

- NA

### Content Changes

- NA

### Screenshot Update

- **Minor updates**:
 
    - **Updated UI Screenshots**: Updated screenshots that were unclear with new ones.
    - **Instruction Refinements**: Enhanced the instructions to improve clarity, and fixed the numbering and rendering issues in the steps.
  
### Testing Notes

- **Testing Date**: 2025-12-31

### Testing Scope 

- Conducted end-to-end testing, RBAC/policy, updated screenshots, and enhanced the instructions for clarity.

</details>


<details>
  <summary>2025-09-22</summary>

## Release Date: 2025-09-23

### Summary of Changes 

- Minor updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.

### Infrastructure Changes

- NA

### Content Changes

- NA

### Screenshot Update

- **Minor updates**:
 
    - **Updated UI Screenshots**: Updated screenshots that were unclear with new ones.
    - **Instruction Refinements**: Enhanced the instructions to improve clarity, and fixed the numbering and rendering issues in the steps.
  
### Testing Notes

- **Testing Date**: 2025-09-22

### Testing Scope 

- Conducted end-to-end testing, RBAC/policy, updated screenshots, and enhanced the instructions for clarity.

</details>


