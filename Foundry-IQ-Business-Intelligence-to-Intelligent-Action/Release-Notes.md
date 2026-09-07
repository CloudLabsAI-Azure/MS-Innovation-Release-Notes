# Foundry IQ - Business Intelligence to Intelligent Action

Welcome to the **Foundry IQ - Business Intelligence to Intelligent Action** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-09-04</summary>

## Release Date: 2026-09-04

### Summary of Changes

- Updated the lab to align with the latest Microsoft Agent Framework experience and prepare for the retirement of Microsoft Workflows. Restructured Exercise 3, including its scenario, overview, task names, content, and screenshots, to use Microsoft Agent Framework. Updated Exercise 4, Task 2, Step 5 to use 15 as the default minimum row count. Additionally, implemented a TPM policy to restrict users from creating additional models beyond the approved models.

### Infrastructure Changes

- Updated Exercise 3 to use Microsoft Agent Framework instead of Microsoft Workflows in preparation for the planned retirement of Workflows.
- Implemented a TPM policy to restrict users from creating additional models beyond the approved models.

### Content Changes

- Updated the Architecture to include Microsoft Foundry models.
- Updated the Getting Started page to replace workflow references with Microsoft Agent Framework.
- Renamed Exercise 3 to Multi-Agent Orchestration with Microsoft Agent Framework.
- Updated all three task names in Exercise 3 to align with the revised lab content.
- Updated the Scenario and Overview sections of Exercise 3 to reflect the Microsoft Agent Framework implementation.
- Restructured Exercise 3 to use Microsoft Agent Framework instead of workflows and updated the associated content accordingly.
- Updated Exercise 4, Task 2, Step 5 to change the default number of rows from 10 to 15, aligning with Microsoft's latest update requiring a minimum of 15 rows.

### Screenshot Updates

- Updated Architecture diagram screenshot in gettingstarted page. 
- Updated all screenshots in Exercise 3 to reflect the transition from workflows to Microsoft Agent Framework.
- Updated the screenshot in Exercise 4, Task 2, Step 5 to align with the revised content and default value of 15 rows.

### Testing Notes

- **Testing Date**: 2026-09-04

### Testing Scope 

Performed end-to-end testing of the updated lab flow, including validation of Exercise 3 using Microsoft Agent Framework. Verified the revised instructions, scenario, overview, task flow, and screenshots, and confirmed that the TPM policy correctly restricts users from creating unapproved models. Also validated the updated default row count of 15 in Exercise 4, Task 2, Step 5 and confirmed the lab is functioning as expected.

---
</details>

<details>
  <summary>2026-06-28</summary>

## Release Date: 2026-06-28

### Summary of Changes

Updated the lab guide to improve lab experience by updating the lab scenarios, refining step-by-step instructions, and refreshing screenshots to match the latest product experience.

### Infrastructure Changes

- Automated assignment of Search Service Contributor role to the Service Principal on the Azure AI Search service for Exc 1 > Task 2 validation.
- Updated the Azure AI Search service deployment to support **Both** API Access Control settings for Keys.

### Content Changes

- Added the **Resize the Virtual Machine View** section in the Getting Started page.
- Refined instructions and summary across the lab guide for better clarity, consistency, and ease of execution.
- Added inline validation steps throughout the lab exercise.

### Screenshot Updates

- Added the screenshot for **Resize the Virtual Machine View** section in the Getting Started page.
- Added the screenshots for the Microsoft Foundry Evaluation runs and results.
- Updated the screenshots for the overall lab exercises to reflect the latest UI.

### Testing Notes

- **Testing Date**: 2026-06-28

### Testing Scope 

- Performed end to end lab testing along with successful validations. Updated the lab content for better clarity.

---
</details>

<details>
  <summary>2026-06-19</summary>

## Release Date: 2026-06-19

### Summary of Changes
Updated the lab guide to improve overall learner experience by aligning instructions with the Microsoft Foundry portal, enhancing clarity, and updating screenshots across all sections.

### Infrastructure Changes
- No infrastructure changes included in this release.

### Content Changes
- Added detailed instructions in Exercise 1 Task 5 for logging into the Microsoft Foundry portal.
- Improved guidance for agent creation in Exercise 2 to reflect the "Create and open in Playground" workflow.
- Added a verification step in Exercise 4 Task 1 Step 5 to view created guardrails.
- Enhanced overall instruction clarity and consistency across the lab guide.

### Screenshot Updates
- Updated all screenshots from Getting Started page to Exercise 4.
- Refreshed images to match the latest Microsoft Foundry portal UI.
- Added new screenshots for:
  - Microsoft Foundry portal login step.
  - “Maybe later” option in Getting Started (Step 5) after Azure login.
  - Agent creation workflow in Exercise 2.
  - Guardrails verification step in Exercise 4.

### Testing Notes
- **Testing Date**: 2026-06-19

### Testing Scope
- Performed end-to-end lab testing.
- Validated updated instructions, screenshots, and workflow alignment with the Microsoft Foundry portal.

---
</details>

<details>
  <summary>2026-06-17</summary>

## Release Date: 2026-06-17

### Summary of Changes

Updated the lab guide to improve lab experience by updating the lab scenarios, refining step-by-step instructions, and refreshing screenshots to match the latest product experience.

### Infrastructure Changes

- Automated assignment of Storage Account Contributor role to the Microsoft Foundry Project managed identity on the Azure Storage Account.
- Automated assignment of Foundry User role to the designated Microsoft Entra ID user at the Microsoft Foundry scope.

### Content Changes

- Refined instructions and summary across the lab guide for better clarity, consistency, and ease of execution.

### Screenshot Updates

- NA

### Testing Notes

- **Testing Date**: 2026-06-17

### Testing Scope 

- Performed end to end lab testing. Updated the lab content for better clarity.

---
</details>

<details>
  <summary>2026-06-13</summary>

## Release Date: 2026-06-13

### Summary of Changes

Updated the lab guide to improve onboarding experience by updating the lab scenarios, refining step-by-step instructions, and refreshing screenshots to match the latest product experience.

### Infrastructure Changes

- Automated provisioning of Microsoft Foundry, Microsoft Foundry Project, and deployment of the GPT-5 and text-embedding-3-large models.
- Automated creation and configuration of an Azure AI Search index for product catalog retrieval using data stored in the designated Azure Blob Storage container.
- Automated assignment of Search Service Contributor and Search Index Data Contributor roles to the Microsoft Foundry Project managed identity on the Azure AI Search service.
- Automated assignment of Foundry Owner and Foundry User roles to the designated Microsoft Entra ID user at the Microsoft Foundry Project scope.

### Content Changes

- Refined instructions across the lab guide for better clarity, consistency, and ease of execution.
- Improved sequencing of steps to reduce confusion during onboarding.

### Screenshot Updates

- Refreshed screenshots to reflect the latest product UI and improve instructional clarity.

### Testing Notes

- **Testing Date**: 2026-06-13

### Testing Scope 

- Performed end to end lab testing. Updated the lab guide for better clarity.

---
</details>

<details>
  <summary>2026-06-09</summary>

## Release Date: 2026-06-09

### Summary of Changes

Updated the lab guide to improve onboarding experience by adding lab scenarios, refining step-by-step instructions, and refreshing screenshots to match the latest product experience.

### Infrastructure Changes

- Automated provisioning of Lab VM resources using ARM templates.
- Automated assignment of the Microsoft Foundry role.

### Content Changes

- Refined instructions across the lab guide for better clarity, consistency, and ease of execution.
- Improved sequencing of steps to reduce confusion during onboarding.

### Screenshot Updates

- Refreshed screenshots to reflect the latest product UI and improve instructional clarity.

### Testing Notes

- **Testing Date**: 2026-06-09

### Testing Scope 

- Performed end to end lab testing. Updated the lab guide for better clarity.

---
</details>
