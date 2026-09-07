# Build and Deploy Agentic AI Solutions

Welcome to the **Build and Deploy Agentic AI Solutions** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com

# Release Notes

<details>
  <summary>2026-08-24</summary>

## Release Date: 2026-08-24

### Summary of Changes 

Updated the challenge guides to correct resource group references, upgrade the chat model from GPT-5.0 to GPT-5.1, and migrate agent knowledge configuration to the new Foundry IQ knowledge base experience. Also restructured the MCP lab setup to include Azure authentication and Python virtual environment steps, and updated MCP Inspector instructions to match the current Inspector UI.

### Infrastructure Changes

- NA

### Content Changes

- Corrected the resource group reference from **ODL-DevelopAgentandAIApp-\<DeploymentID\>-02** to **ODL-DevelopAgentandAIApp-\<DeploymentID\>-01** in lab-01 and lab-03.
- Updated the chat model deployment from **GPT-5.0** to **GPT-5.1** in lab-02, including deployment name and success criteria.
- Replaced the legacy AI Search agent configuration ("Set up a data source via tools") with the new **Foundry IQ knowledge base** flow, including knowledge base creation, adding Azure AI Search index as a source, and connecting the agent to Foundry IQ.
- Added Azure authentication steps (`az account clear`, `azd auth login`) and Python virtual environment setup steps (venv creation, activation, dependency installation) to lab-05.
- Removed the notebook-based package installation step in lab-05, now handled through the virtual environment setup.
- Updated MCP Inspector connection instructions to the current UI (Add Servers, Server ID, Streamable HTTP transport, toggle-to-connect) and tool execution flow (Tools → Execute Tool).
- Improved formatting across lab-05 by converting unnecessary code blocks to inline bold text for resource names, notebook filenames, and variable values.

### Screenshot Update

- NA

### Testing Notes

- **Testing Date**: 2026-08-24

### Testing Scope 

- Verified GPT-5.1 model deployment with Global Standard type and 200000 TPM rate limit
- Validated the new Foundry IQ knowledge base creation and agent connection flow end-to-end
- Confirmed corrected resource group references resolve correctly across lab-01, lab-03, and lab-05
- Tested MCP Inspector connectivity to the weather MCP server via Azure API Management using the updated Add Servers flow
- Verified `get_weather` tool execution returns expected results through MCP Inspector

---

</details>

<details>
  <summary>2026-07-02</summary>

## Summary of Changes

Updated the **Develop Agent Hackathon** lab to align with the latest Microsoft Foundry and Azure portal experience. The challenge and solution guides were refreshed with updated instructions, improved navigation, revised learner guidance, and new screenshots across all five labs. The lab was also updated to use the **GPT-5.1** model in place of **GPT-4o**, ensuring the instructions reflect the current recommended model deployment. Documentation was reorganized to improve clarity and provide a consistent learner experience.

## Infrastructure Changes

- Updated the lab configuration to use **GPT-5.1** instead of **GPT-4o** for model deployments.

## Content Changes

- Updated the **Getting Started** guide with the latest onboarding and navigation experience.
- Revised the **Hackathon Mission** and **Technical Prerequisites** documentation for improved clarity.
- Updated learner instructions across **Lab 1–Lab 5** in the Challenge Guide.
- Updated Solution Guide content across **Lab 1–Lab 5** to match the latest workflow.
- Replaced references to **GPT-4o** with **GPT-5.1** wherever applicable.
- Improved instructional wording, navigation steps, and overall learner experience throughout the lab.
- Removed obsolete content and replaced it with guidance that reflects the current Microsoft Foundry experience.

## Screenshot Updates

- Refreshed screenshots throughout the Challenge Guide.
- Updated screenshots across the Solution Guide to match the current Microsoft Foundry and Azure portal UI.
- Added new screenshots for recently updated workflows and navigation paths.
- Removed outdated screenshots that no longer reflect the current experience.

## Testing Notes

- **Testing Date:** 2026-07-02

## Testing Scope

- Validated the lab end-to-end after all documentation updates.
- Verified GPT-5.1 deployment and updated model references throughout the lab.
- Verified all Challenge Guide instructions across Labs 1–5.
- Verified all Solution Guide instructions across Labs 1–5.
- Confirmed the updated screenshots match the current Microsoft Foundry and Azure portal experience.
- Verified instructional flow, navigation, formatting, and overall learner experience.

---
</details>

<details>
  <summary>2026-05-22</summary>

## Release Date: 2026-05-22
 
### Summary of Changes

- Updated the lab guide by adding a Lab Scenario section to provide users with a clear understanding of the lab objectives and workflow.

### Infrastructure Changes

N/A

### Content Changes

- **Minor updates**: 

    - Updated the lab guide by removing unnecessary characters and correcting grammatical and formatting inconsistencies.

### Screenshot Updates

- Screenshot updates as per the new UI and relevant screenshots updates everywhere required for better user experience
      
### Testing Notes

- **Testing Date**: 2026-05-22

### Testing Scope 

- Executed complete process testing to ensure reliable performance, correct implementation, and seamless operational flow.

---
</details>

