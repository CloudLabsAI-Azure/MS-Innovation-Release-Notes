# GitHub Copilot Java App Modernization

Welcome to the **GitHub Copilot Java App Modernization** lab release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-06-06</summary>

## Release Date: 2026-06-06

### Summary of Changes

- Updated the lab to align with the latest GitHub Copilot App Modernization experience, simplify the modernization workflow, reduce repetitive agent executions, and UI updates. 

### Infrastructure Changes

NA

### Content Changes

- Task 1: Updated the GitHub sign-in steps in VS Code to align with the latest VS Code user interface and authentication experience.
- Tasks 3, 4, and 5: Consolidated the previous modernization tasks (Migrate to Azure Database for PostgreSQL Flexible Server, Azure Blob Storage, and Azure Service Bus using predefined tasks) into two streamlined tasks:
  - Task 3: Generate and Review the Modernization Plan
  - Task 4: Execute the Modernization Plan
  This change was made to align with the latest functionality of the App Modernization extension. Previously, learners could execute each modernization task individually using the Run Task button. As the Run Task option is no longer available in the current experience, the workflow has been updated to first generate a modernization plan using the Create Plan option in the modernization report, and then execute the plan through GitHub Copilot Chat using guided prompts.
- Task 7: Updated the Azure authentication steps to reflect the current sign-in and authentication workflow.

### Screenshot Updates

- Task 1: Updated screenshots for Github sign in VS Code.  
- Task 3 and 4: Added screenshots for modernization plan generation, plan review, and execution plan.
- Task 7: Added screenshots for Azure authentication
  
### Testing Notes

- **Testing Date**: 2026-06-05

### Testing Scope 

- Performed end-to-end lab testing with successful outcomes. Updated the lab guide as per the updated workflow and enhanced the instructions and screenshots. 

---
</details>

<details>
  <summary>2026-05-11</summary>

## Release Date: 2026-05-11

### Summary of Changes

- The lab was thoroughly tested and the content was reviewed and updated, with minor improvements made to the instructions to enhance clarity and accuracy and ensure a smoother learning experience.

### Infrastructure Changes

- Lab instructions were refined to provide clearer and more understandable guidance.

### Content Changes

In the Lab, Task 2 : Following Instructions are  added:
- If prompted, click Allow to grant the required permissions.

- In the Visual Studio Code prompt, click Allow to sign in with GitHub.

- In the account selection prompt, choose odl-user to proceed with authentication.

### Screenshot Updates

N/A

### Testing Notes

- **Testing Date**: 2026-05-11

### Testing Scope 

- Performed end-to-end lab testing with successful outcomes. Updated the lab guide to improve clarity, ensure smooth flow, enhance content accuracy, and align screenshots with the latest UI.


---
</details>


<details>
  <summary>2026-04-02</summary>

## Release Date: 2026-04-02

### Summary of Changes

The lab has been end-to-end, and multiple content, UI alignment, and instructional clarity improvements have been implemented.

### Infrastructure Changes

- Updated the Docker Desktop version in the lab VM setup and revised installation steps to ensure successful execution.

### Content Changes

- Task 1 - Step 6: Enhanced Docker Desktop setup instructions to address runtime issues and ensure compatibility with the latest version.

- Task 1 - Step 30: Documented the “Recommended” and “Custom” assessment options, including step-by-step guidance and supporting screenshots.

- Task 1 - Step 31: Added detailed configuration guidance for selections under the “Recommended” assessment flow.

- Task 1 - Step 33: Updated the lab guide to reflect the latest assessment report interface, including revised screenshots.

- Task 2 - Step 1: Clarified Task 2 completion steps with proper instructions and screenshots to resolve ambiguity.

- Task 2 - Step 2: Added explicit instruction to skip “Fix CVE” and “Generate Unit Tests”, as they are not required for this lab.

- Task 3 - Step 1: Updated UI reference for “Secure Azure Database for PostgreSQL with Managed Identity” to reflect the latest Assessment Report layout.

- Task 6 - Step 4: Corrected UI references from “Run” to “Run Skill / Run Task”, aligned with the latest interface, along with a reference screenshot.

- Task 7: Introduced a clear completion checkpoint for Task 7, including criteria to transition to Task 8.

### Screenshot Updates

- Updated multiple screenshots to improve clarity and align them with the latest UI.

### Testing Notes

- **Testing Date:** 2026-04-02

### Testing Scope

Performed **end-to-end validation** of the lab environment and documentation. Verified all instructions, commands, portal navigation steps, and validated the updated application code and deployment workflow.

</details>

<details>
  <summary>2026-03-16</summary>

## Release Date: 2026-03-16

### Summary of Changes

Updates include refined instructions, standardized task headings and summaries, improved step wording, and alignment with the latest Microsoft portal UI.

### Infrastructure Changes

- Updated the **application source code** used in the lab to resolve issues in the existing implementation.
- Updated the **CloudLabs repository** with the revised application code.
- Modified the **PowerShell setup script** to clone the updated repository during environment setup.

### Content Changes

- Updated the **pom.xml** files for the **web**, **worker**, and **asset-manager** modules.
- Added **PID files** for both the **web** and **worker** services to resolve runtime execution issues.
- Added instructions for **initializing Docker Desktop** in the LabVM.
- Included steps for installing the **required VS Code extensions** and **signing in to GitHub**.
- Added a **workaround in the guide** for the issue where the **resource link cannot be added to the health endpoint skill**.
- Improved formatting and step numbering across all exercises.
- Standardized **Task headings, lab summaries, notes, and instructions** for better clarity and consistency.

### Screenshot Updates

- Updated multiple screenshots to improve clarity and align them with the **latest Microsoft portal UI**.

### Testing Notes

- **Testing Date:** 2026-03-16

### Testing Scope

Performed **end-to-end validation** of the lab environment and documentation. Verified all instructions, commands, portal navigation steps, and validated the updated application code and deployment workflow.

Additionally, connected with **Shashank for review** and incorporated the feedback received.


</details>
