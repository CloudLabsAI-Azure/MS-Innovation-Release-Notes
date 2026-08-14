# Low Code for Pro-Dev in a Day 

Welcome to the **Low Code for Pro-Dev in a Day** Readme.md. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-08-14</summary>

## Release Date: 2026-08-14

### Summary of Changes

Performed end-to-end testing of the lab to validate the Power Platform solution packaging and deployment workflow and ensure the lab content and screenshots are aligned with the latest Power Platform experience.

### Infrastructure Changes

N/A

### Content Changes

- Updated the Power Platform CI/CD workflow to install Power Platform Tools before executing Power Platform actions.
- Updated the `pack-solution` and `import-solution` actions to `@v1`.
- Validated successful solution packaging and deployment to the test environment.

### Screenshot Updates

- Updated screenshots across all labs to reflect the latest Power Platform user interface and workflow.

### Validation

- Validated successful solution packaging and import using the updated CI/CD workflow.

### Testing Notes

- **Testing Date**: 2026-08-12

### Testing Scope

- Performed end-to-end testing of the lab.
- Verified the Power Platform solution packaging and deployment workflow.
- Confirmed successful solution packaging and import into the test environment.
- Updated and verified screenshots across all labs for accuracy and consistency.

</details>

<details>
  <summary>2025-10-10</summary>

## Release Date: 2025-10-10

### Summary of Changes

- The lab has been successfully tested, and the lab content along with validations have been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-10-10

### Testing Scope 

- Performed end to end lab testing and all validations were successful, updated lab guide for better clarity.

</details>

<details>
  <summary>2025-09-10</summary>

## Release Date: 2025-09-10

### Summary of Changes

- The lab has been successfully tested, and the lab content along with validations have been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-09-10

### Testing Scope 

- Performed end to end lab testing and all validations were successful, updated lab guide for better clarity.

</details>

<details>
  <summary>2025-07-22</summary>

### Release Date : 2025-07-22

- **Testing Date**: 2025-07-22

## Infrastructure Changes

**Details:**
- Updated automation script to fix *dev test* environment deployment in power apps portal.
- Resolved the license issue.

## Content Changes
 
- Included explicit navigation steps to ensure users reach the correct development environment.

## Screenshot Updates

- Included multiple screenshots to enhance clarity.

## Testing Notes

- **Testing Date**: 2025-07-22
- **Tested Features**: Inline validations, latest UI changes, decreasing lab provisioning time, complete functionality of the lab.
- **Issues Found**: The lab guide appears to be accurate, with no identified issues. The deployment failure is related to a missing or insufficient PowerApps license.
- **Resolved Issues**: Resolved license discrepancies and improved deployment stability. No significant changes to lab guide instructions, but added additional screenshots to enhance clarity.
  
</details>

<details>
  <summary>2025-06-04</summary>

### Release Date: 2025-06-04

- **Change**: Updated logon script to fix dev test environement deployment in power apps portal, fixed pac and npm packages installation.
- **Testing Date**: 2025-06-04

## Infrastructure Changes

**Change:**
- Updated logon script and fixed the issues.

**Details:**
- The dev test environment was getting failed to get created in power apps portal.
- pac and npm packages were getting failed to install. 
- To make deployment and the logon script to get succeeded, the environment was assigned with **Powerapps Premium** and **Microsoft 365 E3(no teams)** license before the deployment. 

## Content Changes
 
- The overview of all three labs are updated which provides insights on the tasks done in the respective labs.
- Added clear instructions for users to navigate to correct development environment.

## Screenshot Updates

- Screenshots have been updated as per new UI changes and updated instructions.
- Added new screenshots where users need to select right development environment and right files from the virtual machine.
- Getting started page has been updated as per the new UI changes in the CloudLabs.

## Testing Notes

- **Testing Date**: 2025-06-04
- **Tested Features**: Inline validations, latest UI changes, functionality of the lab.
- **Issues Found**: Dev test environment was not showing up in powerapps portal, pac and npm pacakges are not installed.
- **Resolved Issues**: Updated logon script to fix the issues mentioned and need to assign **Powerapps Premium** and **Microsoft 365 E3(no teams)** license before the logon script starts.
---
</details>


