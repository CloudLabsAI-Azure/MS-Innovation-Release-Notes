# Building-the-business-migration-case-with-Windows-Server-and-SQL-Server

Welcome to the **Building the business migration case with Windows Server and SQL Server** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

## Release Notes

<details>
  <summary>2026-08-20</summary>

## Release Date : 2026-08-20

### Summary of Changes

Modernised the retired Microsoft Cloud Workshop lab for CloudLabs delivery and reworked the environment so that it deploys reliably without manual intervention. Retired tooling was replaced with currently supported Microsoft services, the lab now uses a shared Azure SQL Managed Instance so environments are ready in minutes rather than hours, and the lab guide was rewritten throughout to match the current Azure portal experience.

### Infrastructure Changes

- Moved the lab to a shared subscription and shared resource group model. Azure SQL Managed Instance is now pre-provisioned and shared, which removes several hours of provisioning time from every lab launch.
- Lab virtual machines now run in the same virtual network as the Managed Instance, so database migration traffic stays on a private connection rather than a public endpoint.
- The on-premises Hyper-V server is now delivered as a pre-built virtual machine image, replacing a 3.7 GB download and a lengthy in-lab installation.
- Reduced virtual machine sizes across the lab to lower the cost per attendee without affecting the exercises.
- Hardened the deployment scripts so that database setup either completes successfully or reports a clear failure, instead of appearing to succeed with no database present.

### Content Changes

- **Lab 01 — Database migration:**

  - Replaced the retired Azure Data Studio migration extension with SQL Server Management Studio and Azure Database Migration Service.
  - Updated the database restore and backup tasks with clearer steps and verification checks so learners can confirm the database is ready before migrating.
  - Added a new task covering the storage account role assignments required for the migration, which previously caused learners to fail at the migration step.
  - Updated the migration task so each attendee migrates to their own target database on the shared Managed Instance.

- **Lab 02 — Application tier:**

  - Updated the virtual machine size and network selections to match the new environment.

- **Lab 03 — Azure Arc:**

  - Removed the prerequisite installation and restart steps, which are no longer required on the current operating system. This saves approximately 30 minutes and removes a step that failed on the updated image.
  - Updated the Azure Arc onboarding steps to reflect the current portal navigation.

- Added troubleshooting guidance across the lab for the errors encountered during validation, so attendees can resolve common issues without raising a support request.

### Screenshot Updates

- Updated screenshots throughout the lab to reflect the current Azure portal, SQL Server Management Studio, and Azure Arc interfaces.

### Testing Notes

- **Testing Date**: 2026-08-20

### Testing Scope

- End-to-end deployment was validated against the new shared environment, confirming both virtual machines provision correctly and connect privately to the shared Managed Instance.
- The database restore and backup exercises were validated on the deployed environment, and the issues encountered were documented in the lab guide.
---
</details>

For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com
