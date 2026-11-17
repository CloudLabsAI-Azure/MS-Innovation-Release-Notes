# Build, Ground, Evaluate and Govern Enterprise AI Agents

Welcome to the **Build, Ground, Evaluate and Govern Enterprise AI Agents** release notes. This page documents changes from the last testing cycle, including infrastructure, content, screenshots, and other relevant lab updates.

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
  <summary>2026-11-10</summary>

## Release Date: 2026-11-10

## Summary
- Completed the lab onboarding for **Build, Ground, Evaluate and Govern Enterprise AI Agents**. Prepared and reviewed the lab environment, deployment configuration, and lab content to ensure smooth provisioning and execution.

## Infrastructure

* Configured the lab infrastructure using an ARM template, a Custom Script Extension, and a supporting logon script.
* Deployed the lab resources per attendee: Microsoft Foundry resource and project (gpt-5.4-mini and text-embedding-3-small), Azure AI Search, Storage account, Application Insights, Log Analytics workspace, and the lab VM.
* Automated the lab setup: the HR policy index is built in Azure AI Search, and the ready-made Foundry agent (contoso-hr-foundry-agent) is created during deployment.
* Added the required tools, packages, and modules to the deployment (VS Code with the Office Viewer extension, Python, and the Foundry SDK), so the lab environment is ready to use when it launches.
* Added Edge favorites for Copilot Studio, Microsoft Foundry, Outlook, and the Azure portal, and a VS Code desktop shortcut that opens the test-set folder.
* Configured the required policies and access for the lab environment: a custom RBAC role, an allowed-resources policy, and a model-restriction policy that allows only the lab's models and capacity.

## Content

* The lab guide walks users through five exercises: From Pilot to Production; Build and Ground the Agent; Govern: Identity, Permissions & Safe Autonomy; Evaluate and Observe; and Publish and Prove the KPI.
* The Getting Started page includes the lab scenario, objectives, an architecture diagram, an explanation of components, and sign-in steps.
* Added the HR policy documents and the two test sets (Microsoft Foundry and Copilot Studio) to the lab environment.
* Created the presentation deck for the lab: Microsoft Foundry, Microsoft Copilot Studio, governance, evaluation, and tracing.

## Validation

* Verified the lab deployment.
* Confirmed that the required configurations and lab files are present in the lab environment.
* Added built-in validations for Exercise 2 (Copilot Studio agent created) and Exercise 4 (Foundry evaluation created).
* Tested the lab end-to-end from a user's perspective and verified that the lab can be completed successfully.

## Testing Scope

* Tested and validated the lab end-to-end successfully.

</details>
