# Building the Business Migration Case with Windows Server and SQL Server

Welcome to the **Building the Business Migration Case with Windows Server and SQL Server** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-10-06</summary>

## Release Date : 2026-10-06

### Summary of Changes

Added a new exercise on protecting a virtual machine with Azure Backup. Added short explanations across the lab so learners understand why each step is done, not just how to do it. Learners can now also check that the migrated database is complete and reachable from the application server. The Getting Started page now explains every resource in the lab environment and has a new architecture diagram that covers all four labs.

### Infrastructure Changes

- Learners now get the access they need on the shared Azure SQL Managed Instance when the lab is deployed. They no longer run into permission errors at the migration step.

### Content Changes

- **Getting Started:**

  - Added a "Know Your Resources" section that explains every resource in both resource groups and why it is used in the lab.
  - Added a description of how the virtual network is divided, and why this allows a private connection between the virtual machines and the Managed Instance.
  - Updated the scenario, overview, objectives, architecture description, and component list to include the new backup exercise.

- **Exercise 01:**

  - Added a new read-only task that compares the ways to migrate a SQL Server database. It explains why the online method was used and walks through the steps of a cutover (the final switch to the new database).
  - Added a step to open Azure Storage Explorer after signing in, and corrected the name of the upload option.
  - Added the steps to find the storage account in the Azure portal.
  - Added a note that the Managed Instance is shared, so learners may see other databases and should look for the one with their own deployment ID.

- **Exercise 02:**

  - Added a new task where learners connect from the application server to the migrated database and check that it works. Learners test the network connection, confirm the database version, and view the database settings and the largest tables.
  - Added notes that explain why the virtual machine is placed in the same virtual network and subnet as the Managed Instance.

- **Exercise 03:**

  - Added a new read-only task that shows what learners can see and do with the Arc-enabled server, and why this matters for servers that stay on-premises.
  - Updated the steps to find the Hyper-V virtual machine to match the current Azure portal.

- **Exercise 04 — Azure Backup (new):**

  - Added a new exercise that shows how to protect the SQL Server virtual machine with Azure Backup.
  - Learners register the backup service, create a Recovery Services vault, set up a daily backup policy, run a backup on demand, restore the virtual machine disks, and clean up the backup setup.

### Screenshot Updates

- Added screenshots for the new tasks in Lab 01, Lab 02, Lab 03, and Lab 04.
- Added screenshots to the Getting Started page that show the two resource groups.
- Replaced the architecture diagram on the Getting Started page with a new one that includes all four labs.

### Testing Notes

- **Testing Date**: 2026-10-06

### Testing Scope

* Performed end-to-end validation of the Building the Business Migration Case lab after adding the new Azure Backup exercise and updating the screenshots and instructions.
* Verified that all updated and new screenshots accurately reflect the current Azure portal experience.
* Validated the navigation flow, exercise steps, and instructional content against the current Azure portal.
* Confirmed that learners can successfully follow all four exercises using the refreshed screenshots and guidance.
---
</details>

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
