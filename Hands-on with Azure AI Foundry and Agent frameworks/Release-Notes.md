# Hands-on with Azure AI Foundry and Agent frameworks

Welcome to the **Hands-on with Azure AI Foundry and Agent frameworks** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2025-10-06</summary>

### Release Date: 2025-10-06

## Summary of Changes

Minor updates, including clearer screenshots and refined instructions for improved clarity and accuracy. 

## Infrastructure Changes

NA

## Content Changes
 
NA

## Screenshot Updates

  - **Updated Screenshots:** Enhanced screenshots have been updated for better understanding.
  - **Instruction Refinements:** Updated numbering and formatting for better clarity and understanding.

## Validation

Validations are good

## Testing Scope

Conducted end-to-end testing and performance tests passed successfully. RBAC and policy checks and verified cost estimation.

</details>

<details>
  <summary>2025-07-24</summary>

### Release Date: 2025-07-24

- **Testing Date**: 2025-07-24

## Infrastructure Changes

**Details:**
- No infrastructure changes were required in this update.

## Content Changes
 
- Refined lab instructions to improve clarity.

## Screenshot Updates

- Replaced outdated screenshots with new ones reflecting the current UI.

## Testing Notes

- **Testing Date**: 2025-07-24
- **Tested Features**: Full lab flow including all sections and tasks.
- **Issues Found**: NA
- **Resolved Issues**: NA
  
</details>

<details>
  <summary>2025-07-25</summary>

### Release Date: 2025-07-25

- **Testing Date**: 2025-07-25

## Infrastructure Changes

**Details:**
- No infrastructure changes were required in this update.

## Content Changes
 
- Refined lab instructions to improve clarity.

## Screenshot Updates

- Replaced outdated screenshots with new ones reflecting the current UI.

## Testing Notes

- **Testing Date**: 2025-07-25
- **Issues Found**: NA
- **Resolved Issues**: NA
  
</details>

<details>
  <summary>2025-06-04</summary>

<details>
  <summary>2025-07-10</summary>

### Release Date: 2025-07-10

## Infrastructure Changes

NA
## Content Changes

- Lab guide instructions have been updated to reflect the latest steps.
- The Getting Started page has been revised based on the new VM interface
  
## Screenshot Updates

- Updated screenshots throughout the lab guide to match the new UI.
- Added additional screenshots where necessary for better clarity.

## Testing Notes

- **Testing Date**: 2025-07-10

---
</details>

<details>
  <summary>2025-06-18</summary>

### Release Date: 2025-06-18

- **Change**: Downgraded Python packages due to compatibility issues with the latest versions.
- **Testing Date**: 2025-06-18

## Infrastructure Changes

- **azure-ai-projects Package**

   - **Issue:** Exercises 2 to 6 experienced connectivity problems with Azure AI Foundry.
   - **Cause:** The latest version of the `azure-ai-projects` package was not compatible with the current setup.
   - **Solution:** Downgraded the package to version **1.0.0b10** to restore functionality.

- **semantic-kernel[azure] Package**

   - **Issue:** Exercise 6 encountered errors related to this package.
   - **Cause:** The latest version of `semantic-kernel[azure]` was incompatible with the implementation.
   - **Solution:** Downgraded the package to version **1.28.0**, resolving the issue.

- Updated the Python code in the Jupyter Notebooks to resolve the issues that were occurring   

## Content Changes

- Updated lab guide steps with the latest UI present in the Azure portal.
- Getting started page has been updated as per the new UI changes in the CloudLabs. 
  
## Screenshot Updates

- Screenshots have been updated as per the new UI changes and updated instructions.
- Updated lab guide with more screenshots wherever required.
- Getting started page has been updated as per the new UI changes in the CloudLabs.

## Testing Notes

- **Testing Date**: 2025-06-18
- **Tested Features**: Inline validations, latest UI changes, functionality of the lab.
- **Issues Found**: The Latest Python Packages were incompatible with the Jupyter notebooks used in this lab. 
- **Resolved Issues**: Downgraded Python packages that were causing issues for the Jupyter notebooks used in this lab.
---
</details>

