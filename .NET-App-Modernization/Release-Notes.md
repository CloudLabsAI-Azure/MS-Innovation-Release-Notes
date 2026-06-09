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
  <summary>2026-05-27 - Lab guide modernization (Exercises 1-10)</summary>

## Summary

Performed a comprehensive review, language refinement, and technical modernization pass across the App Modernization hands-on lab (Exercises 1–10). The most significant change replaces the retired Data Migration Assistant (DMA) workflow with the supported SQL Server Management Studio (SSMS) Generate Scripts wizard for database assessment and schema migration to Azure SQL Database. All exercises were updated for clarity, consistency with the current Azure portal UI, and accurate step numbering.

## Content

Updated and validated the following lab guides:

- **1.md** – Refined application architecture review steps; updated SSMS connection flow to include the new **Encryption: Optional** option in the Connect to Server dialog; clarified RDP and SQL VM instructions.
- **2.md** – Language and clarity improvements for the Azure Migrate setup and assessment task.
- **3.md** – Refined App Service Migration Assistant assessment steps and screenshots.
- **4.md** – **Major rewrite**: removed the retired DMA-based assessment and Azure Database Migration Service (DMS) workflow. Replaced with:
  - SSMS-based compatibility pre-check using a `sys.objects` audit query against the `PartsUnlimited` database.
  - **SSMS Generate Scripts wizard** for schema-only migration to Azure SQL Database, including Advanced Scripting Options set to **Microsoft Azure SQL Database** as the target engine type.
  - Post-generation script cleanup guidance (Find & Replace for `ALTER DATABASE`, removal of unsupported `CREATE DATABASE` / database-scoped `SET` statements, and explicit database context).
  - Added Assessment Summary callout confirming migration readiness.
- **5.md – 9.md** – Language refinement, step renumbering, and screenshot/image refresh for App Service deployment, CI/CD with GitHub Actions, Azure Functions / Queue Storage / Blob Storage integration, and monitoring exercises.
- **10.md** – Renamed to **Exercise 10: Data encryption using Azure Key Vault (Optional)**; added Task 1 heading, injected DeploymentID into resource names (key vault, storage account, resource group), and added a final **Summary** section with lab completion message.

## Media

Added new screenshots supporting the SSMS-based migration workflow and refreshed multiple existing images:

- Added: `ssms-generate-scripts.png`, `ssms-advanced-scripting.png`, `ssms-advanced-scripting2.png`, `ssms-compat-query.png`, `ssms-compat-results.png`, `ssms-db-context.png`, `ssms-find-replace.png` (1–4), `wizard.png`, `summary.png`, `scriptfinish.png`, `connect-to-target.png`, `Source_details.png`, `After_integration_setup1.png`, `addnewmigrtation.png`, `disconnectrdp.png`, `vmstart.png`, `m38-execute.png`.
- Refreshed: `dma.png`, `m30.png`, `m34.png`, `m37.png`, `m4.png`, `m41.png`, `m42.png`, `m43.png`, `deployschema.png`, `selectobjecttab.png`, `sqlserver.png`, `azsql.png`, `partsun.png`, `dflt2.png`, `dfltapp.png`, `createrepo.png`, `finish.png`, `github-05.png`, `rdp1.png`, `vmip.png`, `After_integration_setup.png`, `01-04-2024(12).png`, `images/map-source.png`.

## Validation

Successfully validated the following in the lab:

- Source SQL Server (2008 R2) connection from SSMS on the SQLVM using SQL Server Authentication with **Trust server certificate** and **Encryption: Optional**.
- `PartsUnlimited` database compatibility audit query returns expected schema objects with no blocking issues.
- SSMS Generate Scripts wizard produces a script targeted at **Microsoft Azure SQL Database** containing all tables, views, stored procedures, users, and constraints.
- Post-generation script cleanup (removal of `ALTER DATABASE`, `CREATE DATABASE`, and database-scoped `SET` statements) executes successfully against the target Azure SQL Database.
- End-to-end web application migration to Azure App Service and connectivity to the migrated Azure SQL Database.
- Exercise 10 (Optional) Key Vault creation and customer-managed key configuration on the storage account.

## Testing Scope

Performed end-to-end testing across Exercises 1–10 to ensure:

- All step numbering, injected variables (`DeploymentID`, `SQLVM Password`, etc.), and screenshots align with the updated flow.
- The new SSMS-based assessment and schema migration path works end-to-end as a replacement for the retired DMA/DMS workflow.
- Renamed/renumbered Exercise 10 displays correctly in the TOC and lab navigation, including the new Optional marker and Summary section.
- No broken image references or stale DMA/DMS instructions remain in Exercise 4 or related guides.

</details>

<details>
  <summary>2022-11-21 - Onboarding</summary>

## Summary

Successfully onboarded and validated the lab environment, Azure Migrate setup, application modernization workflow, Azure App Service deployment, database migration, CI/CD integration, and serverless processing components.

</details>