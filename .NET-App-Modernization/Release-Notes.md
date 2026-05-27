# .NET App Modernization

Welcome to the **.NET App Modernization** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, bug fixes, and other relevant changes for the lab.

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
  <summary>2026-05-21</summary>

## Summary

Performed a comprehensive review, language refinement, and technical modernization pass across all exercises of the App Modernization hands-on lab. The most significant change replaces the retired Data Migration Assistant (DMA) and Azure Database Migration Service (DMS) workflow with the supported SQL Server Management Studio (SSMS) Generate Scripts wizard for database assessment and schema migration to Azure SQL Database. All exercises were updated for clarity, consistency with the current Azure portal experience, and accurate step numbering.

## Content

Updated and validated the following exercises:

- **Exercise 1 – Review the legacy on-premises application and database**: Refined application architecture review steps and updated the SSMS connection flow to include the new **Encryption: Optional** option in the Connect to Server dialog.
- **Exercise 2 – Set up Azure Migrate and perform assessment**: Language and clarity improvements for the Azure Migrate setup and discovery flow.
- **Exercise 3 – Migrate the web application using App Service Migration Assistant**: Refined assessment and migration steps for the PartsUnlimited web application.
- **Exercise 4 – Migrate the on-premises database to Azure SQL Database**: Major rewrite. Removed the retired DMA-based assessment and DMS migration workflow and replaced it with:
  - An SSMS-based compatibility pre-check using a `sys.objects` audit query against the `PartsUnlimited` database.
  - The **SSMS Generate Scripts wizard** for schema-only migration to Azure SQL Database, with Advanced Scripting Options set to **Microsoft Azure SQL Database** as the target engine type.
  - Post-generation script cleanup guidance (Find & Replace for `ALTER DATABASE`, removal of unsupported `CREATE DATABASE` and database-scoped `SET` statements, and an explicit database context).
  - A new Assessment Summary callout confirming migration readiness.
- **Exercise 5 – Configure the App Service and connect to Azure SQL Database**: Language refinement, step renumbering, and updated portal navigation.
- **Exercise 6 – Configure CI/CD using GitHub Actions**: Clarified repository setup, workflow configuration, and deployment validation steps.
- **Exercise 7 – Deploy Azure Functions for order processing**: Refined Function App deployment and Queue Storage integration steps.
- **Exercise 8 – Configure Blob Storage for invoice handling**: Language and step clarity improvements.
- **Exercise 9 – Application monitoring with Azure Application Insights**: Updated monitoring configuration and validation steps.
- **Exercise 10 – Data encryption using Azure Key Vault (Optional)**: Renamed and marked as Optional, added a Task 1 heading, injected `DeploymentID` into resource names (key vault, storage account, resource group), and added a final **Summary** section with a lab completion message.

## Media

Refreshed existing screenshots and added new screenshots across all exercises to reflect the latest Azure portal UI and the new SSMS-based database migration workflow.

## Validation

Successfully validated the following in the lab:

- Source SQL Server (2008 R2) connection from SSMS on the SQLVM using SQL Server Authentication with **Trust server certificate** and **Encryption: Optional**.
- `PartsUnlimited` database compatibility audit returns expected schema objects with no blocking issues.
- SSMS Generate Scripts wizard produces a script targeted at **Microsoft Azure SQL Database** containing all tables, views, stored procedures, users, and constraints.
- Post-generation script cleanup executes successfully against the target Azure SQL Database.
- End-to-end web application migration to Azure App Service and connectivity to the migrated Azure SQL Database.
- CI/CD deployment using GitHub Actions, Azure Functions with Queue Storage, Blob Storage integration, and Application Insights monitoring.
- Exercise 10 (Optional) Key Vault creation and customer-managed key configuration on the storage account.

## Testing Scope

Performed end-to-end testing across Exercises 1–10 to ensure:

- All step numbering, injected variables, and screenshots align with the updated flow.
- The new SSMS-based assessment and schema migration path works end-to-end as a replacement for the retired DMA and DMS workflow.
- Renamed and renumbered Exercise 10 displays correctly in the TOC and lab navigation, including the new Optional marker and Summary section.
- No broken image references or stale DMA/DMS instructions remain in the lab guides.

</details>
