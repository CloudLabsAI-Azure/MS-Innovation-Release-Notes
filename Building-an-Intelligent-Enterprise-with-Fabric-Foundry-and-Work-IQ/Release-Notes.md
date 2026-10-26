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
  <summary>2026-10-07</summary>

## Summary of Changes

Improved the workshop labs with clearer instructions, updated workflows, and refreshed screenshots to better reflect the learner experience and current portal interfaces.

## Content and Workflow Updates

- Added agent-related tasks and supporting instructions, and expanded Power Automate flow guidance.
- Updated navigation and workflow instructions across the labs, including the AI Search indexer process and governance steps.
- Refined examples, scenarios, and sample data to improve consistency and clarity.
- Updated workshop titles and duration estimates across applicable exercises.
- Improved guidance for validating grounded AI responses and assigning lab-specific user roles.

## Screenshot Updates

### Getting Started

- **Architecture:** Updated the architecture diagram to help learners understand the workshop at a glance.
- **Sign in to Microsoft Fabric, Step 7:** Added a screenshot showing the Fabric welcome prompt and the action to dismiss it.

### Exercise 1

- **Task 1, Step 1:** Updated the workspace confirmation screenshot.
- **Task 1, Step 3:** Added a screenshot to guide the File Explorer search.
- **Task 2, Step 1:** Added the solution architecture diagram.
- **Task 2, Step 6:** Updated the Microsoft Foundry resource selection screenshot.

### Exercise 2

- **Task 4, Step 3:** Updated the semantic model setup screenshot.

### Exercise 3

- **Task 2, Steps 4, 6, 7, and 9:** Updated the screenshots for creating and configuring data-driven alerts.
- **Task 3, Steps 9 and 14:** Updated the screenshots for the storage account upgrade workflow.
- **Task 3, Step 15:** Added a screenshot showing the storage container.

### Exercise 5

- **Task 4, Create the Microsoft Team, Step 3:** Updated the team setup screenshot.
- **Task 4, Flow 1, Step 5:** Added a screenshot for signing in to the email action.
- **Task 4, Flow 2, Step 1:** Added a screenshot for creating the Teams notification flow.
- **Task 4, Flow 3, Step 1:** Added a screenshot for creating the Planner task flow.

## Testing Notes

- **Testing Date:** 2026-10-07

## Testing Scope

- Reviewed lab sequencing and updated instructions for clarity and consistency.
- Validated the revised navigation and Power Automate guidance against the documented workflows.
- Checked that updated and added screenshots align with the corresponding learner steps.
- Reviewed the AI grounding and governance guidance.

</details>

<details>
  <summary>2026-10-07</summary>

## Summary of Changes

Implemented content, workflow, and documentation updates across the workshop labs to align with the latest portal experience, improve instructional clarity, enhance the overall learning experience, and ensure greater accuracy for learners.

## Content Updates

- Updated lab guides with the latest portal screenshots and images across the workshop.
- Added a new task with agents, references, and instructions from the lab documentation.
- Upgraded MCP Flow-related steps with the Power Automate flows and supporting content from applicable exercises.
- Updated navigation steps, instructions, and supporting guidance to align with the revised lab workflow.
- Reviewed and refined lab content to ensure consistency following the upgrade of the MCP Flow section.
- Updated workshop titles and duration metadata across lab01, lab02, lab03, and lab07 to better reflect actual completion times.
- Updated the lab guide instructions to use a single indexer consistently throughout the lab, improving clarity, reducing confusion, and making the workflow easier for users to follow.
- Refined lab scenarios and sample datasets by updating region examples and expanding supported region values within Fabric IQ exercises.
- Simplified Power Automate guidance in lab05 by removing redundant publishing steps, standardizing save actions, and updating scenario examples.
- Enhanced AI grounding validation guidance in lab04-new with updated prompts, refreshed screenshots, and clearer explanations of grounded versus fabricated responses.
- Updated governance and security instructions to use lab-specific user accounts and revised role assignment procedures.

## Documentation and Asset Updates

- Refreshed documentation assets with updated screenshots and images across multiple exercises.
- Replaced outdated visuals to reflect the latest portal experience and workflow changes.
- Improved instructional consistency throughout the lab guides following content modernization efforts.

## Testing Notes

- **Testing Date:** 2026-10-07

## Testing Scope

- Validated all lab guides after the upgrade of Prompt Flow and MCP Flow content.
- Verified updated navigation paths and workflow instructions against the current portal experience.
- Confirmed revised workshop metadata and duration estimates are reflected correctly across applicable labs.
- Reviewed Power Automate exercises to ensure updated instructions are accurate and complete.
- Validated AI grounding exercises and expected response behavior using the updated guidance.
- Confirmed screenshots and supporting documentation align with the current user interface.

---

</details>
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

- **Testing Date**: 2026-09-27

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
