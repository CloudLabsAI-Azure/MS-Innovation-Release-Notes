# SQL-AI-App-in-a-day 

Welcome to the **SQL-AI-App-in-a-day** Release-Notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

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
  <summary>2026-08-07</summary>

## Release Date: 2026-08-07

### Summary of Changes 

- Moved the workshop onto the new Microsoft Foundry hubless resource (Previously Azure OpenAI Resource) and upgraded from GPT-4o to GPT-5.1, with both models now pre-deployed automatically via ARM template. Tightened access so learners no longer need Owner on the resource group, using a new custom RBAC role and policy instead. Updated all SQL queries across the workshop to reference the new Foundry endpoint format, restructured all six labs for consistency, and added four new hands-on tasks to round out the 8-hour schedule.

### Infrastructure Changes

- Migrated from a standalone Azure OpenAI resource to the new Microsoft Foundry hubless resource type.
- Migrated the chat model deployment from GPT-4o to GPT-5.1.
- Automated deployment via ARM template: the Foundry resource, the `text-embedding-3-small` model, and the `gpt-5.1` model are now all pre-deployed automatically; no manual model deployment steps are required from learners.
- ARM template now automatically assigns the **Foundry User** RBAC role to the Azure SQL Server's managed identity on the Foundry resource, so learners no longer need Owner access to complete this step manually.
- Removed the **Owner** role assignment on the resource group for learners.
- Added a new **custom RBAC role**, scoped to only what learners need to view resources and copy endpoints, replacing the broader Owner access previously required.
- Added a new **custom Azure Policy** to enforce the above access scope. 

### Content Changes

**Created a separate branch for MS Innovation lab in GitHub repo**

**Lab 01 - Text Search**
- Added a new example showing that even manual abbreviation lists (like "MI") don't scale, and updated the summary table to match.
  
**Lab 02 - Connecting to Foundry**
- Updated credential steps to use Managed Identity instead of an API key — no keys to copy or store anymore.
- Updated the RBAC role name to **Foundry User** (renamed by Microsoft from "Cognitive Services OpenAI User").
- Updated steps to match the current Foundry portal, which now shows only an Endpoint (the old "Target URI" field is gone).

**Lab 03 - Generating Embeddings**
- Updated the embedding generation queries to reference the new Foundry endpoint format, and adjusted them to run in small batches instead of all at once.
- Added two new tasks: one that proves semantic search actually understands meaning (not just keywords), and one that shows embeddings numerically cluster by diagnosis.

**Lab 04 - Vector & Hybrid Search**
- No functional changes; restructured for consistency with the rest of the workshop.

**Lab 05 - Reciprocal Rank Fusion**
- Added a new task letting learners tune the search weighting and see how results shift.

**Lab 06 - RAG with GPT-5.1**
- Switched the model from GPT-4o to GPT-5.1, and updated the SQL queries to reference the new Foundry endpoint and request format.
- Updated how the AI summary text is read from the response to match the new endpoint's response format.
- Added a new task comparing GPT-5.1's "low" vs. "high" reasoning settings.

**All Labs**
- Rewrote every lab into the same Scenario → Overview → Objectives → Tasks → Summary structure.

### Screenshot Update

- Lab 02: Updated screenshots to reflect the current Foundry portal's Endpoint-only view (Target URI and API key fields no longer shown).
- Lab 03: Added new screenshots for the batched embedding generation output and the new Task 5/Task 6 verification queries.
- Lab 05: Added new screenshots for the RRF weight-tuning comparisons (Task 4).
- Lab 06: Added new screenshots for the GPT-5.1 stored procedure output and the reasoning-effort comparison (Task 4).
- Overall, updated all the screenshots as previous screenshots were showing shadows and some of them were blurry. 
  
### Testing Notes

- **Testing Date**: 2026-08-06

### Testing Scope 

- Conducted end-to-end testing of the lab with the new Foundry hubless resource, including the Managed Identity authentication flow, the updated endpoint references across all SQL queries, embedding generation under the new batching approach, the GPT-5.1 RAG procedure, and all four newly added tasks.

</details>

<details>
  <summary>2026-06-11</summary>

## Release Date: 2026-06-11

### Summary of Changes 

-  Updated the lab guide for improved clarity and accuracy, enhancing the overall user experience.

### Infrastructure Changes

- NA

### Content Changes

- Refined a few instructions to improve clarity and enhance the overall user experience.
- Added new Instructions step for creation of ai models task using second approach (model catalog).
- 
### Screenshot Update

- Azure OpenAI: Added navigation screenshots for creating models directly from the project.

- Model Deployments: Documented the "second approach" from the Model Catalog for both Text and Chat model deployments.

- UI Updates: Refreshed the "Getting Started" page with the latest user interface screenshots and details.
  
### Testing Notes

- **Testing Date**: 2026-06-10

### Testing Scope 

- Conducted end-to-end testing of the lab environment. The lab guide was updated with few screenshots and minor improvements to ensure better clarity and user experience

</details>

<details>
  <summary>2026-04-30</summary>

## Release Date: 2026-04-30

### Summary of Changes 

-  Updated the lab guide for improved clarity and accuracy, enhancing the overall user experience.

### Infrastructure Changes

- NA

### Content Changes

- Refined a few instructions to improve clarity and enhance the overall user experience.

- All instructions have been verified to match the existing lab flow, and no new instructions were added.

### Screenshot Update

- All screenshots have been validated to align with the latest UI, with no additional screenshots introduced.
  
### Testing Notes

- **Testing Date**: 2026-04-30

### Testing Scope 

- Conducted end-to-end testing of the lab environment. The lab guide was updated with few screenshots and minor improvements to ensure better clarity and user experience

</details>
