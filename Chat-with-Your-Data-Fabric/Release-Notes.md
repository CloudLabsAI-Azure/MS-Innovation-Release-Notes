# Chat with Your Data Fabric

Welcome to the  **Chat with Your Data Fabric** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

 `Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-08-21</summary>

## Release Date : 2026-08-21

### Summary of Changes

Updated Lab 1's deployment workflow from manual, UI-driven multi-step processes to fully automated command-line-based automation. Restructured lab tasks from 4 to 3, added 21 new instructional screenshots, completely rewrote deployment steps with infrastructure-as-code emphasis, automated build scripts, CLI-based agent testing, and on-behalf-of (OBO) authentication configuration. Lab now aligns with production-grade DevOps practices and provides a more efficient, reproducible learning experience.


### Infrastructure Changes

- Enhanced post-deployment automation pipeline to support integrated build and configuration workflow
- Introduced on-behalf-of (OBO) authentication configuration via PowerShell script for secure user identity delegation
- Updated provisioning scripts to support scenario-based deployment (Retail and Insurance use cases)
- Added container build and push workflow to Azure Container Registry (ACR) via automated bash script
- Implemented Python-based solution builder with scenario selection and Fabric resource provisioning

### Content Changes

- **Terminology & Formatting Updates:**
  - "Workshop Scenario" → "Lab Scenario"
  - "Overview" → "Lab Overview"
  - "Objectives" → "Lab Objectives"
  - Simplified zoom level icon description for clarity
  - Standardized objective bullet formatting

- **Task Restructuring (4 Tasks → 3 Tasks):**
  - **Task 1:** Create Fabric workspace and link with Copilot-enabled capacity (unchanged)
  - **Task 2:** Deploy Azure infrastructure AND build solution (expanded scope)
    - New prerequisites added:
      - Backend runtime stack configuration: `azd env set BACKEND_RUNTIME_STACK dotnet`
      - Azure Developer CLI version check with upgrade path for v1.23.8
      - Fabric workspace ID reuse: `azd env set FABRIC_WORKSPACE_ID <workspace-id>`
      - Container build and push: `bash ./infra/scripts/build/build-and-push-acr.sh`
      - Python virtual environment setup with dependency installation via `uv`
      - Separate Azure CLI authentication: `az login` (distinct from `azd auth login`)
      - Scenario-based solution build: `python infra/scripts/post-provision/00_build_solution.py --scenario retail|insurance`
  - **Task 3:** Test deployed AI agent from CLI AND configure on-behalf-of authentication (completely replaced)
    - Removed manual Azure Portal-based authentication setup
    - Added interactive CLI-based agent validation: `python infra/scripts/post-provision/06_test_agent.py`
    - Added OBO authentication setup: `pwsh -File ./infra/scripts/post-provision/setup_app_authentication.ps1`
    - Support for Retail and Insurance scenario sample questions
    - Direct end-to-end validation of Fabric Lakehouse, Ontology, Data Agent, and Foundry agent integration

- **Removed Workflows:**
  - Manual Microsoft identity provider configuration via Azure Portal
  - Web UI-based application testing
  - Task 4 (formerly "Testing the application")

### Screenshot Updates

Added 21 new instructional screenshots to reflect current CLI workflows, Azure UI, and automation processes:

**Repository Setup & Codespaces (5):**
- `utt.png` - GitHub "Use this template" button
- `cr.png` - Repository creation form
- `ccom.png` - Codespace creation initiation
- `ccom1.png` - Trust folder confirmation
- `2-5.png` - Codespace setup wizard

**Environment Configuration (4):**
- `back.png` - Backend runtime stack setup
- `azd.png` - Azure Developer CLI version check
- `azdv1.png` - AZD version 1.23.8 upgrade and conditional configuration
- `azdup.png` - Infrastructure provisioning prompts and location selection

**CLI Workflows & Authentication (4):**
- `py.png` - Python virtual environment creation
- `pp.png` - Dependency installation with `uv`
- `l1n1.png` - AZD authentication login flow
- `l1n2.png` - Successful Azure user login confirmation

**Agent Testing & Validation (3):**
- `ps1.png` - Agent test script execution
- `help.png` - Sample questions display
- `as.png` - Agent response examples

**OBO Authentication (1):**
- `as1.png` - PowerShell authentication script execution

**Additional Utilities (4):**
- `wsid.png` - Fabric workspace ID entry
- `ls.png` - Azure subscription selection
- `ls1.png` - Solution build script execution
- `azdd.png` - Resource cleanup operations 

### Testing Notes

- **Testing Date**: 2026-08-21

### Testing Scope

- End-to-end validation of the lab deployment and exercises was performed. The Copilot Studio portal and GitHub UI changes were reviewed to confirm that the lab instructions align with the latest interface.
---
</details>

<details>
  <summary>2026-06-19</summary>

## Release Date : 2026-06-19

### Summary of Changes

Updated the lab guide to align with the latest Microsoft Fabric, Copilot Studio, GitHub Codespaces, and Azure deployment experiences. Refreshed navigation, authentication flows, screenshots, and instructional content to improve accuracy and reduce learner confusion. Additionally, introduced a custom Azure Policy for the lab environment to better control resource usage. 

### Infrastructure Changes

- Added a custom Azure Policy for the lab environment to restrict resource creation based on the requirements of the hands-on exercises.

### Content Changes

- **Lab 01:**

  - Updated steps for GitHub Repo creation as a step to select the template is added during the creation process. 
  - Added a Power BI to Microsoft Fabric navigation step before workspace creation to reflect the current portal experience.
  - Updated GitHub Codespaces and `azd up` deployment guidance for subscription selection behavior and deployment flow.
  - Added a final application view screenshot after successful authentication so learners can verify expected results.

- **Lab 02:**

  - Updated the Fabric Agent integration flow with revised Copilot Studio navigation to match the latest UI.
  - Added a new end-of-lab conclusion summarizing the complete Microsoft Fabric Data Agent and Copilot Studio integration experience.
  - Refreshed multiple headings, notes, instructions, and explanatory text for improved clarity and consistency with the latest Microsoft experiences.

### Screenshot Updates

- Updated screenshots throughout the lab to reflect the latest Microsoft Fabric, Copilot Studio, GitHub Codespaces, and Azure portal interfaces. 

### Testing Notes

- **Testing Date**: 2026-06-19

### Testing Scope

- End-to-end validation of the lab deployment and exercises was performed. The Copilot Studio portal and GitHub UI changes were reviewed to confirm that the lab instructions align with the latest interface.
---
</details>

<details>
  <summary>2026-06-01</summary>

## Release Date : 2026-06-01

### Summary of Changes

Enhanced the lab guide to improve learner onboarding, deployment clarity, and overall navigation. Added scenario-based introductions, expanded explanations for deployment and authentication steps, simplified technical guidance, and reorganized setup instructions to provide a more structured learning experience.

### Infrastructure Changes

- Implemented GitHub SSO automation to streamline repository authentication and access during lab setup.
- Enhanced deployment provisioning scripts to integrate **GitHub SSO-based** access workflows. Reduced dependency on manual GitHub credential configuration during lab execution.

### Content Changes

- **Getting Started Page:**

  - Added a concise Scenario Overview section to introduce the solution context.
  - Added a Core Components section describing the key technologies and resources used throughout the lab.
  - Improved explanations of the lab environment, including VM usage and lab guide layout.
  - Enhanced deployment and authentication guidance with clearer instructions and contextual information.
  - Added section icons to improve readability and navigation.

- **Lab 01:**

  - Added a concise Scenario Overview aligned with the retail sales analytics business use case.
  - Enhanced explanations for `azd up`, azd `auth login`, AI agent setup scripts, and Microsoft Fabric deployment scripts to clarify the expected outcomes of each command.
  - Updated GitHub authentication instructions to reflect the new SSO-based sign-in experience. Removed legacy authentication guidance that required additional manual configuration steps.
  - Improved Azure authentication and resource configuration instructions.
  - Reorganized deployment prompts into a structured table format to improve navigation and learner understanding.

- **Lab 02:**

  - Added a concise Lab Scenario describing unified analytics and enterprise data exploration using Microsoft Fabric.
  - Reduced emphasis on implementation details and provided additional business context for learners.

### Screenshot Updates

- **Getting Started Guide**: Updated Environment tab and Split Window screenshots to match the latest UI experience.
- Refreshed existing screenshots and added new screenshots across **Lab 01, Lab 02** to match the latest Azure DevOps and GitHub UI experience. 

### Testing Notes

- **Testing Date**: 2026-05-29

### Testing Scope

- End-to-end validation of the lab deployment and exercises was performed. The Copilot Studio portal UI changes were reviewed to confirm that the lab instructions align with the latest interface.
---
</details>

<details>
  <summary>2026-05-04</summary>

## Release Date : 2026-05-04

### Summary of Changes

- Updated lab instructions and screenshots to improve clarity and align with the latest Copilot Studio and Fabric portal UI.


### Infrastructure Changes

N/A

### Content Changes

- **Lab 1 – Task 2 (Step 4):** Added instructions to proceed with the next steps to retrieve the device verification code.  
- **Lab 2 – Task 1 (Steps 7–8):** Added instructions to test the agent using sample prompts.  
- **Lab 2 – Task 2 (Step 3):** Added instructions to select a team from the dropdown to proceed with the Copilot sign-up process.  


### Screenshot Updates

- **Lab 2 – Task 1 (Step 3):** Updated screenshots to reflect the latest UI changes in the **Add data to data agent** experience.  
- **Lab 2 – Task 1 (Step 4):** Corrected screenshots to align with the updated step numbering.  
- **Lab 2 – Task 1 (Steps 7–8):** Added new instructions and screenshots for testing the agent using sample prompts.  

- **Lab 2 – Task 2 (Step 3):** Updated screenshots to reflect recent UI changes during Copilot sign-up, including the new step to select a team before proceeding.  
- **Lab 2 – Task 2 (Step 5):** Updated screenshots to align with the latest UI changes when creating and editing an agent.  

- **Lab 2 – Task 2 (Step 17):** Updated screenshots to reflect the latest UI while reviewing the Fabric data agent.  
- **Lab 2 – Task 2 (Step 19):** Updated screenshots to reflect the latest UI changes when disabling the Knowledge settings for the agent.  

### Testing Notes

- **Testing Date**: 2026-05-04

### Testing Scope

- End-to-end validation of the lab deployment and exercises was performed. The Copilot Studio portal UI changes were reviewed to confirm that the lab instructions align with the latest interface.
---
</details>
<details>
  <summary>2026-03-26</summary>

## Release Date : 2026-03-26

### Summary of Changes

- Updated lab instructions and screenshots to improve clarity and align with the latest Copilot Studio portal UI.

- Added a note recommending the use of a local system for now, as the Copilot Studio UI on the VM is not displaying all features.

### Infrastructure Changes

N/A

### Content Changes

NA

### Screenshot Updates

- Getting Started Page: Updated screenshots for lab guide and environment view.

- Lab 1 – Task 1 (Step 10): Updated the screenshots to reflect the new UI, as the task flow was previously in preview mode.

- Lab 2 – Task 1 (Steps 1): Updated the screenshots to reflect the latest UI, as the Data Agent was previously in preview mode in Microsoft Fabric.

- Lab 2 – Task 2 (Steps 5): Updated the screenshots to reflect the change in the agent model, which was previously set to the default.

- Lab 2 – Task 2 (Steps 18): Updated the screenshots to reflect the Copilot agent settings, where the “Use information from web” option is now enabled, whereas it was previously disabled.

- Lab 2 – Task 2 (Steps 22 and 23): Updated the screenshots to reflect the latest UI changes while adding a channel to the agent.

### Testing Notes

- **Testing Date**: 2026-03-26

### Testing Scope

- End-to-end validation of the lab deployment and exercises was performed. The Copilot Studio portal UI changes were reviewed to confirm that the lab instructions align with the latest interface.
---
</details>
