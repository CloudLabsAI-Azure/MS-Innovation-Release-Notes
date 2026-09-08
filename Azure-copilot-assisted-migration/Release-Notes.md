# Azure copilot assisted migration

Welcome to the **Azure copilot assisted migration** Readme.md. In this, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots,[...]

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
  <summary>2026-09-07</summary>

## Release Date: 2026-09-07

### Summary of Changes

Updated the Azure Copilot-assisted Migration lab guide (Getting Started, Exercises 1–5) to match current portal/VS Code UI, fix two functional gaps found during testing (hardcoded target region, wrong deploy resource group), and clarify that Exercises 4–6 use a separate Java app (`asset-manager`) unrelated to the SmartHotel VMs migrated in Exercises 1–3. Screenshots were refreshed extensively across all files, and Exercise 5 was restructured to remove obsolete Flask/Gunicorn-era tasks and add the ACR credential/secret steps actually required.

### Infrastructure Changes

- Exercise 3: Target region changed from hardcoded "West Europe" to a dynamic `<inject key="region">` value, so it matches the region of the environment's pre-provisioned resources instead of conflicting with them.
- Exercise 4: Deployment target resource group corrected from `AzureMigrateRG-<DeploymentID>` to `SmartHotelHostRG-<DeploymentID>`, so the app reuses the pre-provisioned App Service (`smarthotelapp...`) and Container Registry (`smarthotelacr...`) instead of provisioning duplicate infrastructure.

### Content Changes

- **GettingStarted.md**
  - Added a sign-in error troubleshooting note.
  - Corrected the "Welcome to Microsoft Azure" pop-up instruction (Cancel → Maybe later) to match current UI.
  - Formatting cleanup: numbered-list renumbering, trailing whitespace, inline GitHub username placement.
- **Exercise1.md**
  - Fixed a broken numbered list that was resetting mid-task; renumbered sequentially through step 33.
  - Formatting cleanup: blockquote/note indentation, trailing whitespace.
- **Exercise2.md**
  - Formatting cleanup: code-block indentation, nested-note formatting for the "Download PLZ artifacts" fallback.
- **Exercise3.md**
  - Added Destructive Operation Warning guidance during Terraform PLZ deployment.
  - Added Enable MSI step on the Migrations page (fixes migration-tracking permissions issue).
  - Fixed the ASR installer's Microsoft Update tab instruction (was directing to a greyed-out "Off" option; now just "select Next").
  - Corrected mismatched callout numbers and "Execute Replicate" → "Execute migration" button-text reference.
  - Added a 20–30 minute deployment / coffee-break note.
- **Exercise4.md**
  - Scenario clarity: added an explicit "How This Exercise Relates to Exercises 1–3" section explaining Exercises 4–6 use the separate `asset-manager` app, and that "SmartHotel" naming is just the shared lab environment name, not a functional dependency.
  - Task 2: Updated VS Code trust-folder workflow (Manage → Trust → Close) to match current dialog; clarified Target Service selection wording.
  - Task 3: Replaced vague "click PostgreSQL Database found" navigation with explicit uncheck/Create Plan steps, run separately for the DB and S3 storage issues.
  - Task 5: Updated deployment prompt to specify a single-container strategy (web module only, no separate worker deployment); added note for when Copilot doesn't return commands, fallback prompt to request them directly.
- **Exercise5.md**
  - Task restructuring: removed the obsolete "Update Deployment Workflow" task and the Flask/Gunicorn/SQLite environment-variable table (mismatched app), renumbering Tasks 5–9 down to Tasks 5–7.
  - Task 1: Added visual guidance for repository creation (profile icon → Repositories).
  - Task 2: Added a note to verify the secret name matches, and to note the web app name for later verification.
  - Task 3: Added new ACR username retrieval steps (Container registries → Access keys → copy Username).
  - Task 4: Now requires three secrets instead of two — added `ACR_USERNAME` alongside the existing `AZURE_WEB_APP_PUBLISH_PROFILE` and `ACR_PASSWORD`.
  - Task 5 (renumbered, was Task 6): Simplified to just clearing the startup command field — no Flask config needed for a container deployment.
  - Task 7 (renumbered, was Task 9): Updated health endpoint from `/health` to `/actuator/health` (Spring Boot Actuator default), with a fallback note if it 404s.

### Screenshot Updates

- **Getting Started:** `envtab.png`, `splittab.png`, `github-homepage.png` (replaced outdated versions); `signin-error.png`, `maybelater.png` (new, support added notes).
- **Exercise 1:** `lab-p1.png` (replaces outdated appliance wizard screenshot), `ex1-p1.png` (discovery source save step).
- **Exercise 2:** `ex2-p1` through `ex2-p6` (replace six outdated Azure Copilot response screenshots).
- **Exercise 3:** `ex3-p1` through `ex3-p11` (PLZ deployment and Hyper-V registration flow); `ex3-p11.png` specifically supports the new Enable MSI note; `ex3-p9.png` supports the corrected Microsoft Update tab step.
- **Exercise 4:** `E4T2S3-0609.png`, `E4T2S4-0609.png` (Task 2, new trust-folder dialog); `E4T3S1-0609.png` through `E4T3S4a-0609.png` (Task 3, explicit Create Plan steps); `E4T4S2c-0609.png` (Task 4); `E4T5S2-0609.png` (Task 5, containerize step); `ex4-p2.png`, `ex4-p3.png` (Docker Desktop skip note).
- **Exercise 5:** `E5T1S1-0609.png` (Task 1, profile → Repositories); `E5T2S3-0609.png` (Task 2, web app name note); `E5T3S5-0609.png`, `E5T3S6-0609.png`, `E5T3S7-0609.png` (Task 3, ACR username retrieval); `acr-username.png` (Task 4, new secret); `E5T5S2-0609.png`, `E5T5S3-0609.png` (Task 5, cleared startup command); `E5T6S3-0609.png` (Task 6); `E5T7S7-0609.png` (Task 7, `/actuator/health` check).

### Testing Notes

- **Testing Date:** 2026-09-07

### Testing Scope

- Completed and validated Exercises 1–4 end-to-end (Azure Migrate discovery, assessment, VM migration, and app modernization).
- Identified and fixed the Exercise 4 deployment gap (wrong target resource group causing duplicate infrastructure), then completed Exercises 5 and 6 (CI/CD pipeline setup and monitoring/optimization) against the corrected deployment.

---
</details>
