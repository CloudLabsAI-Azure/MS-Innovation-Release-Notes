# Getting Started with Microsoft Foundry, Agents and MCP framework

Welcome to the **Getting Started with Microsoft Foundry, Agents and MCP framework** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-06-25</summary>

## Release Date: 2026-06-25

### Summary of Changes

- Replaced the DeepSeek-R1 model with DeepSeek-V3.2 in the Getting Started page and align with the latest supported model availability.

- Refactored ex-8: removed unnecessary steps and added a note about model selection in VS Code Copilot Chat for MCP server setup.Updated VS Code screenshot to align with instructions.Updated DeepSeek Task 5 in ex-3.

### Infrastructure Changes

N/A

### Content Changes

- Documentation & Naming: Updated all references of DeepSeek-R1 to DeepSeek-V3.2 across the Getting-started page and ex-1 and ex-3.
- Model replaced from DeepSeek-R1 to DeepSeek-V3.2

- Exercise 3: Updated DeepSeek's Task 5 instructions.
   - Replaced the model from DeepSeek-R1 to DeepSeek-V3.2 
   - corrected the instruction for model_deployment_name as deepseek-V3.2

- Exercise 8 Optimization:
  - Cleaned up the exercise by removing redundant steps.
  - Added a helpful note regarding model selection in VS Code Copilot Chat when adding the MCP server.
  - updated the screenshot with latest ui of copilot studio agent creation step to add a mcp server tool.

### Screenshot Update
- In getting started page updated the architecture diagram with correct model name for deepseek.
- In Exercise - 1
    - updated the screenshot for Deepseek-V3.2 selection and deployment.
    - vscode welcome page screenshot is updated with correct option selection to continue without signing option.
- Exercise - 3
    - Updated the folder naming DeepSeek-V3 and updated the image.
    - DeepSeek is updated to supporting model -> DeepSeek-V3.2
- In Exercise - 8
  - In vs code copilot chat model selection and mcp server adding step is updated to select right one.
  - In copilot studio added screenshots to select custom connectors naviagtion step and mcp tool adding option screenshot UI updated. 

### Testing Notes

**Testing Date:** 2026-06-23

### Testing Scope

- Updated the testing scope for this lab by validating the steps, refining them for the correct DeepSeek model and instructions, and fixing the notes, UI screenshots, and any mismatched screenshots so they now align with the content."

</details>

<details>
  <summary>2026-06-12</summary>

## Release Date: 2026-06-12

### Summary of Changes

This release focuses on improving the overall learning experience by introducing structured lab scenarios, refining content clarity, enhancing markdown formatting, and updating visual assets across the lab. These updates ensure better contextual understanding and smoother navigation for learners.

### Infrastructure Changes

N/A

### Content Changes

- Added **Lab Scenario sections** at the beginning of **Exercise 1 through Exercise 6 and Exercise 8** for better contextual alignment with the overall lab narrative.
- Updated **gettingstarted.md** and **github-access.md** with improved formatting and added scenario overview.
- Standardized markdown formatting across all files:
  - Updated note formatting to use `>` for consistency
  - Added clarification notes for UI navigation
  - Improved overall readability and structure
- Performed minor text refinements:Fixed token reduction instructions, clarified kernel selection steps and removed redundant image references

### Screenshot Update

- Added new images (foundry-toggle, feedback, select-project, copilot-studio-toggle, feedback-studio)  
- Updated existing images (adconjk, gitlogdon2)  
- Aligned visuals with latest UI  

### Testing Notes

**Testing Date:** 2026-06-12

### Testing Scope

Validated all updated content end-to-end to ensure:
- Scenario sections align with each exercise flow  
- Instructions are clear, accurate, and properly sequenced  
- Markdown formatting is consistent across all files  
- Screenshots correctly reflect the current UI  
- No formatting, navigation, or content inconsistencies introduced  

</details>
<details>
  <summary>2026-05-29</summary>

## Release Date: 2026-05-29

### Summary of Changes

This release includes updates to multiple lab exercises and supporting assets to improve clarity, accuracy, and alignment with the current workshop workflow. The updates ensure a smoother and more consistent learner experience across all exercises.

### Infrastructure Changes

NA

### Content Changes

- Updated instructions in **Exercises 1, 3, and 6** for improved clarity and consistency.
- Refined and improved **GitHub access documentation (`github-access.md`)**.
- Updated image assets (`gg_e6_14.png`, `vswelcome.png`) to reflect the latest UI changes.
- Removed the **GitHub Copilot section from Exercise 8** to eliminate outdated content.
- Improved overall readability and structure of lab instructions.

### Screenshot Update

- Updated outdated screenshots to match the latest UI for relevant lab steps.
- Ensured image consistency across exercises for better learner understanding.
- Replaced or refreshed visuals impacted by workflow or UI changes.

### Testing Notes

**Testing Date:** 2026-05-29

### Testing Scope

Validated all updated exercises end-to-end to ensure:
- Step accuracy and correct sequencing
- Alignment with current Azure and lab workflow
- Proper rendering of updated screenshots and images
- Removal of GitHub Copilot content
- No formatting or instruction inconsistencies introduced

---

</details>

<details>
  <summary>2026-05-08</summary>

## Release Date: 2026-05-08

### Summary of Changes

Updated multiple lab exercises to align with the latest Azure AI Foundry, VS Code, GitHub Copilot, and Power Automate experiences. Improvements include refreshed screenshots, clearer navigation guidance, updated workflows, and troubleshooting notes to provide a smoother learner experience.

### Infrastructure Changes

NA

### Content Changes

- Updated instructions across Exercises 1, 2, 3, 4, 6, and 7 to match the latest product UI and workflows.
- Refreshed guidance for accessing Project Connection Strings, model deployments, API keys, and notebook files.
- Improved VS Code onboarding instructions, including welcome screen, Trust Authors prompt, and authentication guidance.
- Added troubleshooting steps for scenarios where the `azd` command is not recognized.
- Updated GitHub Copilot workflow steps and screenshots to reflect the latest VS Code experience.
- Improved Power Automate and Copilot Studio instructions to align with the latest agent creation workflow.
- Added clearer navigation guidance and corrected minor inconsistencies identified during validation.

### Screenshot Update

* Refreshed outdated screenshots across multiple exercises to align with the latest UI in following technologies Azure AI Foundry, VS Code, GitHub Copilot, and Power Automate.
* Standardized screenshots for improved readability and consistency throughout the lab.

### Testing Notes

**Testing Date:** 2026-05-06

### Testing Scope

Completed end-to-end validation of lab exercises, including updated UI workflows, notebook execution steps, authentication flow handling, GitHub Copilot integration, Power Automate agent creation, and troubleshooting guidance. Also ensured there is content accuracy, and screenshot alignment with the current UI experience.

---
</details>
<details>
  <summary>2026-03-19</summary>

## Release Date: 2026-03-19

### Summary of Changes

- Minor refinements were made across multiple exercises to improve navigation clarity, enhance step-by-step guidance, and ensure better alignment with the latest UI and workflow.

### Infrastructure Changes

- N/A

### Content Changes

- Updated navigation steps to access Microsoft Foundry from the Azure portal home page
- Added clarity for copying and using the Project connection string for downstream tasks.
- Improved folder selection guidance for opening the correct lab directory in VS Code.
- Refined notebook execution instructions to ensure users can correctly locate and run cells.
- Updated environment configuration steps, including SERVERLESS_MODEL_NAME changes and reversion guidance.
- Added prerequisite step to install a specific Semantic Kernel version for compatibility.
- Improved MCP server access steps, including URL formatting and browser navigation.
- Minor updates to GitHub/Copilot sign-in guidance for enabling AI features.

### Screenshot Updates

- Refreshed and aligned screenshots across exercises to match updated instructions and UI changes.
      
### Testing Notes

- **Testing Date**: 2026-03-19

### Testing Scope 

- End-to-end validation of updated navigation, configuration steps, notebook execution, and MCP server setup to ensure consistency and usability across all exercises.
>
---
</details>

<details>
  <summary>2026-03-03</summary>

## Release Date: 2026-03-03

### Summary of Changes

- Removed the MFA setup steps from the Getting Started page.
- Fixed the rendering issue in Exercise 1.
- Updated screenshots for Exercise 7 – Task 1 (Steps 10, 11, and 13) to reflect the latest UI changes in the GitHub Chat interface.
- Validation for GitHub repository cloning has been implemented in the script to ensure the repository is cloned correctly, along with the creation of a virtual environment and installation of the required packages for smooth and reliable execution.

### Infrastructure Changes

- Validation for GitHub repository cloning has been implemented in the script to ensure the repository is cloned correctly, along with the creation of a virtual environment and installation of the required packages for smooth and reliable execution.

### Content Changes

- Removed the MFA setup steps from the Getting Started page.
- Fixed the rendering issue in Exercise 1.

### Screenshot Updates

- Updated screenshots for Exercise 7 – Task 1 (Steps 10, 11, and 13) to reflect the latest UI changes in the GitHub Chat interface.
      
### Testing Notes

- **Testing Date**: 2026-03-03

### Testing Scope 

-Conducted end-to-end lab testing, all validations were successful. Updated the lab guide to improve clarity and enhance the overall user experience.

---
</details>


<details>
  <summary>2026-02-11</summary>

## Release Date: 2026-02-11

### Summary of Changes

- Implemented minor UI updates for Microsoft Foundry and Copilot Studio, and improved instructions for better clarity.
- User reported confusion while logging into Git-hub so instructions were revised properly and notes were added wherever required.
- Aligned screenshots wrt testing checklist.
- Some of instructions related to commands were missing checked with TO and added those as well.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Revised and updated screenshots to align with current UI changes, enhancing instructional accuracy and user experience.
      
### Testing Notes

- **Testing Date**: 2026-02-11

### Testing Scope 

- Performed end to end lab testing, and all validations were successful. Updated the lab guide for better clarity.

---
</details>

<details>
  <summary>2026-01-06</summary>

## Release Date: 2026-01-06

### Summary of Changes

- Implemented minor UI updates for Microsoft Foundry and Copilot Studio, and improved instructions for better clarity.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Revised and updated screenshots to align with current UI changes, enhancing instructional accuracy and user experience.
      
### Testing Notes

- **Testing Date**: 2026-01-05

### Testing Scope 

- Lab content, code functionality, UI alignment, and clarity of revised screenshots.

---
</details>

<details>
  <summary>2026-12-10</summary>

## Release Date: 2025-12-10

### Summary of Changes

- Implemented UI updates for Microsoft Foundry and Copilot Studio, including refreshed screenshots and improved instructional guidance.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Revised and updated screenshots to align with current UI changes, enhancing instructional accuracy and user experience.
      
### Testing Notes

- **Testing Date**: 2025-12-09

### Testing Scope 

- Lab content, code functionality, UI alignment, and clarity of revised screenshots.

---
</details>

<details>
  <summary>2025-11-13</summary>

## Release Date: 2025-11-13

### Summary of Changes

- Replaced unclear screenshots to align with the new CloudLabs UI.

### Infrastructure Changes

N/A

### Content Changes

- Tested the labs E2E and made updates that have been incorporated to ensure consistency across the lab.

### Screenshot Updates

- Revised and updated screenshots to align with current UI changes, enhancing instructional accuracy and user experience.
      
### Testing Notes

- **Testing Date**: 2025-11-12

### Testing Scope 

- Lab content, code functionality, UI alignment, and clarity of revised screenshots.

---
</details>

















