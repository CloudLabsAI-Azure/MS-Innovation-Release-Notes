# Getting Started with Microsoft 365 Copilot Cowork

Welcome to the **Getting Started with Microsoft 365 Copilot Cowork** release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

**This is a newly onboarded lab.**

# Release Notes

<details>
  <summary>2026-07-28</summary>

## Release Date: 2026-07-28

## Summary of Changes

Completed end-to-end onboarding of the **Getting Started with Microsoft 365 Copilot Cowork** lab. The lab was authored as a 60-minute introduction to the agentic Cowork workspace inside Microsoft 365 Copilot, built around the Contoso Connect product launch scenario. Content was created across six tasks covering interface orientation, environment seeding, cross-source synthesis, guardrail behaviour, scheduled automation, and custom skill creation. Screenshots were captured against the current Cowork interface, licensing and tenant configuration were validated, and the lab was tested end-to-end and finalized for production.

## Infrastructure Changes

- Validated Microsoft 365 Copilot licensing and confirmed Copilot Cowork availability for the lab user
- Verified tenant-level enablement of Cowork
- Verified Cowork's access to Outlook, Calendar, and Microsoft Teams, and confirmed approval prompts appear before each write action
- Verified Temporary Access Pass sign-in flow and lab user provisioning
- Confirmed deployment configuration and environment readiness for the full lab duration

## Content Changes

- **Getting Started Page**: Authored lab scenario, overview, objectives, prerequisites, architecture description, and component explanations; added architecture diagram and standard CloudLabs navigation sections
- **Task 1**: Created interface orientation content including a Copilot Chat versus Copilot Cowork comparison table, sign-in flow, and Auto model selector guidance
- **Task 2**: Structured environment setup into three sub-tasks seeding sample emails, calendar events, and a Teams channel message, building the dataset used by later tasks; added concise-output instructions to all seeding prompts to limit unnecessary response generation
- **Task 3**: Authored cross-source synthesis content generating a Launch Status briefing from inbox, calendar, and Teams data, followed by conversion into a formatted Word document
- **Task 4**: Added a deliberate impossible-scheduling request to demonstrate Cowork's guardrail behaviour, where it explains the conflict and offers alternatives rather than silently violating constraints
- **Task 5**: Authored scheduled task automation content and configured the step to skip the immediate test run, avoiding duplicate execution of the same workflow
- **Task 6**: Created custom skill build and trigger content, including review of the generated skill quality report
- Added a disclaimer noting that Cowork outputs are AI-generated and may vary between users and sessions, directing learners to follow the documented workflow rather than expecting identical results

## Screenshot Updates

- Captured all screenshots across the lab aligned with the current Microsoft 365 Copilot Cowork interface
- Added visuals covering the Cowork home screen and model selector
- Added approval card and Workspace pane visuals across the email, calendar, and Teams seeding steps
- Added Outlook and Microsoft Teams verification visuals confirming seeded content
- Added generated briefing and Word document output visuals
- Added guardrail response, scheduled task configuration, and custom skill quality report visuals

## Testing Notes

- **Testing Date**: 2026-07-28

## Testing Scope

- Validated the lab end-to-end within the 60-minute duration
- Verified all six tasks including email, calendar, and Teams seeding, briefing synthesis, Word document generation, guardrail handling, scheduled task creation, and custom skill build and trigger
- Confirmed sign-in flow and Cowork availability, and verified data was read and written correctly across Outlook, Calendar, and Microsoft Teams
- Verified approval prompts appear correctly on each write action
- Confirmed content accuracy, sequencing, formatting, and expected outputs
- Verified screenshots align with the latest Microsoft 365 and Cowork UI
- Successfully pushed all finalized changes to production

---
</details>