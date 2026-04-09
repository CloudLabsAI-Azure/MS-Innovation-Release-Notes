# Fabric Database Mirroring

Welcome to the **Fabric Database Mirroring** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-04-04</summary>

## Release Date: 2026-04-04

### Summary of Changes

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues and enhanced the instructions wherever needed.

### Infrastructure Changes

NA

### Content Changes

N/A

### Screenshot Updates

In all the lab tasks updated with Fabric UI screenshots to reflect the latest UI and improve clarity.
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>
<details>
  <summary>2026-03-06</summary>

## Release Date: 2026-03-06

### Summary of Changes

Resolved deployment and configuration issues impacting Fabric mirroring of SQL Managed Instance and PostgreSQL in Lab 3 and Lab 6, respectively. Minor updates were also made by adding clearer, up-to-date UI screenshots.

### Infrastructure Changes

- Lab 3 Task 2 issue fix: 
  - Updated the API version used for the deployment of the SQL MI instance. The previous API version caused failures while retrieving DMV information during the Fabric mirroring. Updating the API version fixed the issue. 

- Lab 6 Task 1 issue fix:
  - Enabling the Fabric mirroring for PostgreSQL was failing. PostgreSQL was deployed on the Burstible SKU Tier, which is no longer supported for Fabric mirroring. Hence, we updated the template to deploy PostgreSQL with the General Purpose tier, which resolved the issue. 

### Content Changes

N/A

### Screenshot Updates

Updated few of the screenshots to reflect the latest UI and improve clarity.
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end validation of the lab, verified that all the Tasks are working as expected without any issues. 

---
</details>

<details>
  <summary>2026-01-24</summary>

## Release Date: 2026-01-24

### Summary of Changes

Made minor updates by adding clearer, up-to-date UI screenshots.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

N/A
      
### Testing Notes

- **Testing Date**: 2026-01-24

### Testing Scope 

Performed end-to-end architecture validation and verification of prerequisites.

---
</details>

<details>
  <summary>2025-12-26</summary>

## Release Date: 2025-12-26

### Summary of Changes

Made minor updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity, improve accuracy, and ensure a smoother learning experience.  

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced screenshots to match the latest user interface.
      
### Testing Notes

- **Testing Date**: 2025-12-26

### Testing Scope 

Performed end-to-end architecture validation, including RBAC and policy compliance checks, and verification of prerequisites.

---
</details>

<details>
  <summary>2025-10-08</summary>

<details>
  <summary>2025-08-26</summary>

## Release Date: 2025-08-26

### Summary of Changes

Updated the ARM template, screenshots, and instructions.  

### Infrastructure Changes

- Updated the API Versions of the resources in the ARM template, as all of them were older versions.
- Updated the Custom Policy

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced the screenshots with clearer ones and enhanced the instructions. 
      
### Testing Notes

- **Testing Date**: 2025-08-25
- **Issue:** In Lab 4 Task 3, after connecting to the Snowflake database, the table did not appear following replication. Sometimes, it may take longer than expected for the table to show up. We are currently investigating this further. For now, a note has been added to continue to task 5 in case this error occurs, as from task 5, the tasks are independent and not blocked by this step.

### Testing Scope 

 Conducted end-to-end architecture validation, RBAC/policy checks, and instructions and screenshots enhancements.

---
</details>

<details>
  <summary>2025-07-31</summary>

## Infrastructure Changes

NA

## Content Changes
 
  - Instructions are enhanced for user better understanding.

## Screenshot Updates

  - Updated Enhanced screenshots with clear instructions.
  - Added numbers in the screenshots to follow step by step.

## Testing Notes

- **Testing Date**: 2025-07-31

---
</details>


<details>
  <summary>2025-05-16</summary>

## Infrastructure Changes

NA

## Content Changes

NA

## Screenshot Updates

  - **Getting Started**: Enhanced with an updated architecture diagram.
  - **Lab 01**: Improved guidance by refining steps and addressing display-related adjustments.
  - **Lab 02**: Clarified instructions to account for UI behavior and ensured accuracy in query details.
  - **Lab 03**: Structured action items with numbering for better readability.
  - **Lab 05**: Refined instructions to reflect accurate data handling and outputs.


## Testing Notes

- **Testing Date**: 2025-05-16

---
</details>

