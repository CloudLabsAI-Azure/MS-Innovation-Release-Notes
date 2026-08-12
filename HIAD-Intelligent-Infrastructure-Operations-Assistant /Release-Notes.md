# HIAD: Intelligent Infrastructure Operations Assistant

Welcome to the **HIAD: Intelligent Infrastructure Operations Assistant** workshop release notes. In this page, we will document the changes made during the latest testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

For any further details or inquiries, feel free to reach out to the CloudLabs support team.

**Email Support:** cloudlabs-support@spektrasystems.com

# Release Notes

<details>
  <summary>2026-08-12</summary>

## Release Date: 2026-08-12

## Summary of Changes

Updated the **HIAD: Intelligent Infrastructure Operations Assistant** lab to align the learning flow, Microsoft Foundry agent architecture, Azure infrastructure instructions, telemetry validation, Streamlit orchestration, and end-to-end alerting experience with the current implementation.

## Infrastructure Changes

- Updated the lab content according to the latest Microsoft Foundry architecture, including the codebase files used for application-level orchestration of the agents.
- Updated the documented architecture to reflect sequential invocation of the three Microsoft Foundry agents through the Streamlit application.
- Updated the model references and supporting configuration to align with the current lab implementation.

## Content Changes

- **Challenge 1**
  - Improved the scenario and overview to explain the data collection, intelligence, orchestration, and alerting layers.
  - Added clearer explanations for the resource group, VM, Log Analytics, DCR, Foundry project, model deployment, telemetry verification, and Event Grid configuration.
  - Improved numbered instructions and portal navigation guidance.
  - Added explicit success criteria and configuration values learners must capture.

- **Challenge 2**
  - Refined CPU, memory, and disk stress-test instructions using Azure CLI Run Command.
  - Improved KQL-based telemetry validation.
  - Added explicit success criteria for stress-test completion and expected telemetry behavior.
  - Added Microsoft documentation references for Run Command, Log Analytics queries, and the Perf table.

- **Challenge 3**
  - Improved the Infrastructure-Metrics-Analyzer agent creation and configuration flow.
  - Added clearer instructions around the permanent agent name and its use by the Streamlit application.
  - Added validation of structured agent output.

- **Challenge 4**
  - Added the Anomaly-Detection-Agent and Remediation-Advisor-Agent creation, configuration, testing, and success criteria.
  - Updated the architecture to reflect **independent Foundry agents orchestrated by the application layer**, rather than automatic Connected Agents hand-off.

- **Challenge 5**
  - Improved Streamlit dashboard setup and live infrastructure analysis instructions.
  - Clarified the connection between Log Analytics, Microsoft Foundry agents, Event Grid, and Logic Apps.
  - Added clearer validation of live agent responses and alert processing.

- **Challenge 6**
  - Updated the end-to-end scenario to reflect the client-side three-agent orchestration model.
  - Increased the CPU stress-test duration from 5 minutes to 15 minutes to provide sufficient telemetry for analysis.
  - Improved validation of the dashboard analysis, CRITICAL anomaly detection, Event Grid publication, Logic App execution, and AI-generated email alert.

- **Overview / Getting Started**
  - Updated the overall architecture and learning objectives to describe application-orchestrated multi-agent processing.
  - Updated authentication terminology to Azure CLI credentials.
  - Added clearer learner environment and VM guidance.
  - Added a **Resize the Virtual Machine View** section with an instructional screenshot.

## Screenshot Updates

- Added and updated screenshots across the challenges to reflect the latest Azure Portal, Microsoft Foundry, Streamlit, Event Grid, Logic App, and lab-environment interfaces in both the challenge guides and solution guides.
- Updated screenshots where the portal UI or learner workflow changed.
- Added `resize-vm-guide.png` to document the lab guide/VM pane resizing experience.

## Testing Date

**2026-08-08**

## Testing Scope

- Reviewed the updated challenge flow from **Challenge 1 through Challenge 6**.
- Validated consistency of:
  - Microsoft Foundry agent terminology.
  - Three-agent orchestration architecture.
  - `gpt-5-mini` model references.
  - Azure resource names and configuration instructions.
  - KQL telemetry validation.
  - Streamlit-to-Foundry workflow.
  - Event Grid and Logic App alerting flow.
  - Challenge success criteria and navigation.
- Reviewed updated and newly added screenshots referenced by the lab guides.
- Verified that the final challenge reflects the current client-orchestrated agent workflow and end-to-end alert validation.

</details>