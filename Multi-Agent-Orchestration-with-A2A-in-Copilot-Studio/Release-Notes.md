# Multi-Agent Orchestration with A2A in Copilot Studio

Welcome to the **Multi-Agent Orchestration with A2A in Copilot Studio** release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

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
  <summary>2026-11-11</summary>

## Release Date: 2026-11-11
## Summary of Changes

Completed a content and environment refresh for the **Multi-Agent Orchestration with A2A in Copilot Studio** lab. Screenshots, instructions, and the lab environment were updated to match the latest Microsoft Copilot Studio and Microsoft Fabric experience.

## Infrastructure Changes

- Replaced the broad access role with a least-privilege custom role for the lab user, with read access to all lab resources.
- Added the Foundry User role assignment for the lab user on the lab resource group.
- Added a custom policy that limits the resource types, SKUs, and model deployments allowed in the lab resource group.
- Updated the lab to use the **gpt-5.4** model in place of **gpt-4o**.
- Updated the VM sku from **d2s_v3** to **d2s_v5**

## Content Changes

- Updated the instructions across all exercises to match the latest Microsoft Copilot Studio and Microsoft Fabric UI.
- Added inject keys wherever possible so that lab-specific values appear directly in the guide.
- Added the Architecture and Architecture Diagram sections to the Getting Started page.
- Updated the Agent2Agent connection steps to use the agent message endpoint.
- Added the missing formula step to the business hours guardrail topic.
- Added a lab summary, reference links, and a closing section at the end of the lab.
- Removed the final deployment exercise. The lab now contains seven exercises.
- Corrected grammar, punctuation, and formatting, and applied a consistent heading style across the lab guide.

## Screenshot Updates

- Updated all screenshots to the latest Microsoft Copilot Studio and Microsoft Fabric UI.
- Blurred the Deployment ID, user ID, and other sensitive information in the screenshots.
- Updated the Agent2Agent connection screenshot to match the revised steps.
- Added a screenshot for the guardrail formula step.

## Testing Notes

- **Testing Date**: 2026-11-11

## Testing Scope

- Completed a full walkthrough of the lab environment to ensure seamless end-to-end execution.
- Mapped and confirmed that all screenshots align with the updated interface for visual clarity.
- Verified all step-by-step navigation paths and learner instructions against the latest live UI elements.
- Verified that the lab user can complete all exercises with the updated role and policy.

---
</details>

<details>
  <summary>2026-09-07</summary>

## Release Date: 2026-09-07
## Summary of Changes

Completed onboarding and end-to-end testing for the **Multi-Agent Orchestration with A2A in Copilot Studio**. All content updates, infrastructure updates, and screenshot changes were completed successfully. The lab was thoroughly reviewed, finalized, and all changes were pushed to production.

## Infrastructure Changes

N/A

## Content Changes

N/A

## Screenshot Updates

- Captured screenshots covering multi-agent architecture and host and specialist agent configuration.
- Added visuals for A2A communication, agent orchestration, and Microsoft Fabric Data Agent integration.
- Added monitoring, troubleshooting, guardrails, and agent interaction verification visuals.
- Added deployment and testing visuals across Microsoft Teams, Microsoft 365 Copilot, and Web channels.

## Testing Notes

- **Testing Date**: 2026-06-18

## Testing Scope

- Completed a full walkthrough of the lab environment to ensure seamless end-to-end execution.
- Mapped and confirmed that all screenshots perfectly align with the updated interface for visual clarity.
- Verified all step-by-step navigation paths and learner instructions against the latest live UI elements.

---
</details>
