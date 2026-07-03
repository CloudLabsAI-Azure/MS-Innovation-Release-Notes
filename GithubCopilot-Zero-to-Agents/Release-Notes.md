# GitHub Copilot - Zero to Agents lab

Welcome to the **GitHub Copilot - Zero to Agents lab** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com

# Release Notes

<details>
  <summary>2026-06-30</summary>

## Release Date: 2026-06-30
 
### Summary of Changes

- Updated the architecture overview and refreshed all lab screenshots to align with the latest Visual Studio Code and GitHub Copilot user interface. Improved component descriptions in the Getting Started section for better learner understanding.

### Infrastructure Changes

- No infrastructure changes.

### Content Changes

- **Getting Started:**  

  1. Added an updated architecture diagram aligned with the solution architecture description.
  2. Expanded the explanation of architecture components to provide additional context and clarity.

- **Exercise 1** : 

  1. Refreshed GitHub Copilot chat window screenshots across all tasks to reflect the current Visual Studio Code experience.
  2. Updated screenshots to capture minor option and terminology changes within the GitHub Copilot chat interface.
  3. Improved instructional clarity by ensuring screenshots accurately match the current workflow.


### Screenshot Updates

- Refreshed all Visual Studio Code screenshots across the lab.
- Updated GitHub Copilot chat window screenshots to reflect the latest UI.
- Replaced screenshots impacted by option and terminology changes within the chat experience.
- Added the updated architecture diagram in the Getting Started section.
      
### Testing Notes

- **Testing Date**: 2026-06-29

### Testing Scope 

End-to-end validation of the complete lab guide, including the Getting Started section, architecture diagram and component descriptions, all task instructions, Visual Studio Code workflows, GitHub Copilot chat interactions, refreshed screenshots, hyperlink validation, instructional sequencing, and overall content formatting to ensure alignment with the current user interface and expected learner experience.

---
</details>

<details>
  <summary>2026-05-25</summary>

## Release Date: 2026-05-25
 
### Summary of Changes

- Updated the Environment tab screenshot as per the latest UI changes and added a note to close the pop-ups.

### Infrastructure Changes

- npm installation was failing in Exercise 1 Task 1 Step 13 because Node 26 is not supported by better-sqlite3@12.5.0. Updated the ARM template to use Node 22 LTS.

### Content Changes

- **Minor updates**:

  - Added notes to cancel the pop-ups.

### Screenshot Updates

 - On the Getting Started page, updated the screenshots for the Environment tab and Split Window function.
 - In Exercise 1 Task 1 Step 3, updated the screenshot for GitHub sign-in.
      
### Testing Notes

- **Testing Date**: 2026-05-25

### Testing Scope 

- Performed end-to-end testing of all lab tasks to ensure alignment with instructions.

---
</details>

<details>
  <summary>2026-04-20</summary>

## Release Date: 2026-04-20
 
### Summary of Changes

- Content updates, refined instructions to improve understanding and clarity.   

### Infrastructure Changes

N/A

### Content Changes

- **Minor updates**: 

    -Updated few instructions to align with latest flow of the lab 

### Screenshot Updates

N/A
      
### Testing Notes

- **Testing Date**: 2026-04-20

### Testing Scope 

- Completed end to end testing and validated all the steps

- Reviewed the lab guide and rendering as well

---
</details>

<details>
  <summary>2026-04-01 - Onboarding</summary>

### Summary
- Successfully onboarded the GitHub Copilot: Zero to Agents lab. The lab environment, Copilot configurations, and end-to-end lab workflow have been validated. 
 
### Infrastructure

- Provisioned and configured the required lab environment, including:
  - Lab VM with pre-installed Visual Studio Code and required extensions.
  - Pre-cloned OctoCAT Supply repository with working backend and frontend services
  - Node.js runtime and required dependencies for local application execution
  - Docker environment for container-based scenarios

### Content 

- Integrated the lab guide aligned with the TOC, which includes:
  - Step-by-step instructions for Ask mode and Agent mode usage
  - Hands-on scenarios for prompt engineering, multi-file changes, and feature implementation
  - Tasks covering security review, Docker hardening, and CI/CD enhancements
  - GitHub workflow integration for repository creation, commit, and push operations
  - Advanced scenarios demonstrating AI-assisted planning, testing, and automation (MCP concepts)

### Validation

- Successfully validated the following in the lab:
  - Application setup and execution (backend + frontend) in the lab VM
  - GitHub Copilot functionality across inline suggestions, chat, and agent workflows
  - Prompt-based generation of APIs, tests, and documentation
  - Multi-file agent execution and controlled application of changes
  - Docker build and run workflow with UI validation
  - GitHub integration, including repository creation, commit, and push

### Testing Scope 
- Performed end-to-end testing of all lab tasks to ensure alignment with instructions.
---
</details>

