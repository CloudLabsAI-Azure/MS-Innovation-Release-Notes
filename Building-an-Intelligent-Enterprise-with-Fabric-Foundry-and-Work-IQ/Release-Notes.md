# From Data to Decisions: Building an Intelligent Enterprise with Fabric IQ, Foundry IQ, and Work IQ

Welcome to the **From Data to Decisions: Building an Intelligent Enterprise with Fabric IQ, Foundry IQ, and Work IQ** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-09-27</summary>

## Summary of Changes

Bug fixes across Exercises 1–6 resolving Copilot availability, Azure AI Search permissions, Power Automate and Copilot Studio issues, and Activator alert configuration.

## Content Updates

**Exercise 1**: Added a step in Before We Begin to enable the required Copilot settings in Fabric Admin portal > Tenant settings

**Exercise 2**: Resolved Copilot not showing in Power BI (fixed via the Exercise 1 tenant settings step)

**Exercise 3**: Resolved Copilot option disabled in Fabric notebooks (fixed via the Exercise 1 tenant settings step), fixed Activator alert creation in Task 2 (select an empty report area before creating the alert, condition changed to Changes, check frequency set to every 5 minutes)

**Exercise 4**: Resolved the permission error in Task 4, Step 7 (fixed via environment update)

**Exercise 5**: Clarified Send an email dynamic content steps in Flow 1, changed Save draft to Publish for Flows 2 and 3, replaced the custom prompt in Topic 1 to fix empty alert emails, changed the Topic 3 due date to a one-week-from-today formula to fix the Planner BadGateway error

**Exercise 6**: Resolved Activator alert not firing in Tasks 1 and 2 (fixed via the Exercise 3, Task 2 changes)

## Infrastructure Changes

- Enabled system-assigned managed identity on Azure AI Search in the ARM template
- Added a deployment script to assign the Storage Blob Data Reader role to the Search managed identity on the storage account

## Screenshot Updates

- **Exercise 1**: Added Fabric Admin portal tenant settings with Copilot enabled
- **Exercise 3**: Updated Activator alert setup in Task 2 (empty report area, Changes condition, 5-minute check)
- **Exercise 5**: Updated Power Automate steps in Task 4 (Use dynamic content in Flow 1, Publish in Flows 2 and 3) and Copilot Studio topics (Topic 1 prompt, Topic 3 due date formula)

## Testing Notes

- **Testing Date**: 2026-09-26

## Testing Scope

- Verified Copilot availability in Power BI and Fabric notebooks after enabling tenant settings
- Verified Azure AI Search managed identity and role assignment on a fresh deployment
- Validated Exercise 4 completes without permission errors
- Validated Power Automate flows publish and run successfully
- Verified Copilot Studio alert emails contain content
- Verified Copilot Studio creates Planner tasks with the correct due date
- Tested end-to-end crisis injection with the Activator alert firing in Exercise 6
- Confirmed all screenshots match current UI implementations

---

</details>

<details>
  <summary>2026-09-10</summary>

## Summary of Changes

Content refinement across all 7 exercises with updated platform references, improved navigation, and new screenshots.

## Content Updates

**Exercise 1**: Refined scenario narrative, updated model references (gpt-5.1, text-embedding-3-small), enhanced Foundry portal navigation

**Exercise 2**: Streamlined lakehouse workflow, simplified semantic model creation, enhanced Power BI report generation with Copilot

**Exercise 3**: Added Copilot for Gold layer generation, simplified Activator alerts, improved AI Search data export workflow

**Exercise 4**: Updated Foundry navigation (New Foundry experience), clarified RAG pipeline setup, enhanced business scenario testing

**Exercise 5**: Added Power Platform environment setup, simplified Copilot Studio agent creation, built 3 Power Automate flows, detailed MCP topic routing

**Exercise 6**: Streamlined crisis injection workflow, simplified validation across email/Teams/Planner outputs

**Exercise 7**: Enhanced RBAC, RLS configuration, guardrails setup, compliance audit logging

## Infrastructure Changes

- Updated model deployments: `gpt-5.1` and `text-embedding-3-small`
- Updated resource naming: `aisearch-<DeploymentID>`
- Enhanced Power Platform environment provisioning
- Verified Microsoft Teams integration

## Screenshot Updates

- Added new screenshots across all exercises
- Updated Foundry portal UI (New Foundry toggle, Build menu)
- Refreshed Power Platform and Copilot Studio workflows
- Enhanced Power Automate configuration visuals

## Key Improvements

- Clearer language with removed redundancy
- Updated all platform references to current versions
- Improved step-by-step guidance with specific parameters
- Added emoji headers for better scannability

## Testing Notes

- **Testing Date**: 2026-09-10

## Testing Scope

- Validated all 7 exercises for technical accuracy
- Verified model deployment references (gpt-5.1, text-embedding-3-small)
- Confirmed Foundry portal navigation paths (New Foundry experience)
- Tested Power Platform environment provisioning workflow
- Verified Copilot Studio agent creation and publishing
- Validated Power Automate flow configurations
- Confirmed Azure AI Search indexing and knowledge base setup
- Tested end-to-end crisis simulation scenario
- Verified governance and security configuration steps
- Confirmed all screenshots match current UI implementations

---

</details>

<details>
  <summary>2026-07-24</summary>

## Summary of Changes

Completed onboarding and end-to-end testing for the **From Data to Decisions: Building an Intelligent Enterprise with Fabric IQ, Foundry IQ, and Work IQ** lab. All content updates, infrastructure updates, and screenshot changes were completed successfully. The lab was thoroughly reviewed, finalized, and all changes were pushed to production.

## Infrastructure Changes

- Validated the ARM deployment workflow and environment readiness for the lab.
- Verified RBAC permissions, custom role assignments, and usage policies required for successful lab execution.
- Confirmed pre-provisioned resources, sample datasets, and licensing prerequisites.

## Content Changes

- Completed content onboarding across all exercises.
- Updated instructions, notes, and navigation flow for improved learner experience.
- Reviewed and updated lab content to ensure consistency and accuracy.

## Screenshot Updates

- Updated screenshots across the lab to align with the latest implementation.
- Verified all images match the current Azure, Microsoft Fabric, Microsoft Foundry, and Microsoft 365 experience.
- Refreshed screenshots for updated workflows and instructions.

## Testing Notes

- **Testing Date**: 2026-07-24

## Testing Scope

- Completed end-to-end testing of the entire lab.
- Verified all exercises, tasks, and deployment workflows.
- Confirmed content accuracy, formatting, navigation flow, and expected outputs.
- Verified screenshot alignment with the latest user interface.
- Successfully pushed all finalized changes to production.

---

</details>
