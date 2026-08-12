# Building Security Copilot Agents Using Microsoft Sentinel Data

Welcome to the **Building Security Copilot Agents Using Microsoft Sentinel Data** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

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
  <summary>2026-08-12</summary>

## Release Date: 2026-08-12

### Summary of Changes

Updated the lab guide to align the optional MCP workflow with the Microsoft Sentinel MCP Triage experience. The release includes updated task descriptions, MCP guidance, architecture content, terminology, and investigation scenarios based on successful end-to-end testing.

### Infrastructure Changes

N/A

### Content Changes

- Updated the lab **Overview** to describe the Microsoft Sentinel MCP Triage workflow.
- Updated the **Objectives** to reflect the revised Task 1–5 flow and MCP Triage activities.
- Updated **Environment Context** and **Scenario** to align with security incident investigation.
- Updated Task 1 terminology from **Data Lake Readiness** to **Security Data Readiness** where applicable.
- Removed the dependency statement that MCP requires an active Sentinel Data Lake for the optional MCP workflow.
- Updated **Task 4** to use the **Microsoft Sentinel MCP Triage server** instead of the previous Data Exploration/Data Lake-based MCP flow.
- Updated Task 4 titles, objectives, MCP explanation, connection instructions, and validation criteria to reflect MCP Triage.
- Added guidance explaining **MCP Triage**, including its role in incident, alert, and entity investigation.
- Updated **Task 5** to focus on security incident investigation using natural language through MCP Triage.
- Replaced the previous raw telemetry/process-level investigation prompts with validated incident-based prompts.
- Updated Task 5 scenarios to cover incident retrieval, severity filtering, affected users and devices, multi-device investigation, lateral movement indicators, and investigation summaries.
- Updated the **KQL vs MCP** comparison to distinguish incident triage through MCP Triage from deeper and customized investigation using KQL.
- Updated the **What You Learned**, **When to Use Each Method**, and **Summary** sections to reflect the new MCP Triage workflow.
- Updated terminology throughout the guide to consistently use **MCP Triage** where applicable.

### Screenshot / Architecture Updates

- Updated the architecture diagram to reflect the revised lab workflow and optional MCP Triage path.
- Updated the architecture flow to show:
  - Microsoft Sentinel
  - Security Copilot Investigation Agent (NL2Agent)
  - Code-First Agent (YAML)
  - Microsoft Sentinel MCP Triage
  - VS Code + GitHub Copilot
  - Natural-language security incident investigation
- Removed the representation of Sentinel Data Lake as a required component of the optional MCP investigation flow.

### Testing Notes

- **Testing Date**: 2026-08-12

### Testing Scope

- End-to-end validation of the updated MCP workflow was completed successfully.
- Verified the Microsoft Sentinel MCP Triage connection using `https://sentinel.microsoft.com/mcp/triage`.
- Validated security incident retrieval using natural-language prompts.
- Validated high-severity incident filtering and incident status retrieval.
- Validated incident summarization, including affected users, devices, and other entities.
- Validated multi-device incident investigation and incident progression across `dc01` and `SMB01`.
- Validated lateral movement and credential access indicators returned through incident investigation.
- Validated generation of an executive investigation summary using natural language.
- Confirmed the updated Task 4 and Task 5 workflow is functional and aligned with the tested MCP Triage capabilities.

</details>

<details>
  <summary>2026-07-13</summary>

## Release Date: 2026-07-13

### Summary of Changes

Minor updates were applied to the lab guide to align with the latest Microsoft Defender portal UI and improve the overall learner experience. The release includes updated screenshots, formatting corrections, workflow improvements and minor content fixes.

### Infrastructure Changes

N/A

### Content Changes

- Updated images in Task 1 referring to the latest Microsoft Defender portal UI. 
- Updated the Getting Started page by fixing broken image references, restructuring heading levels, removing duplicate introductory content, updating the architecture diagram, and adding the missing Next button image.
- Improved lab readability by correcting Markdown formatting and note styles.
- Reordered Task 3 steps to follow the correct workflow (review YAML in VS Code before opening the Security Copilot portal).
- Added new learner guidance for the VS Code welcome screen and corrected the lab file path (C:\LabFiles\).
- Added troubleshooting notes for agent execution and activity generation to help learners recover from delayed responses.
- Added a missing configuration step in Task 4 to select Global as the configuration target.
- Updated terminology from Password to Temporary Access Pass to match the current authentication experience.

### Screenshot Updates

- Updated UI Screenshots:
  - Replaced multiple screenshots across Task 1 to reflect the latest Microsoft Defender portal UI.
  - Updated the Security Copilot agent creation screenshot in Task 2.
  - Added a new screenshot for the Global Configuration Target selection in Task 4.
  - Updated screenshots in Task 5 for Advanced Hunting navigation and KQL query results to match the latest portal experience.
  - Updated the architecture diagram and fixed image rendering issues on the Getting Started page.

### Testing Notes

- **Testing Date**: 2026-07-12

### Testing Scope 

- End-to-end lab validation completed successfully, verified all updated workflow steps and instruction sequence. Confirmed all screenshots align with the current Microsoft Defender and Security Copilot portal UI, and verified all image references, formatting, and hyperlinks are functioning correctly.

---
</details>

<details>
  <summary>2026-06-04</summary>

## Release Date: 2026-06-04

### Summary of Changes

Minor updates were applied to the lab guide to align with the latest Microsoft Defender portal UI changes.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: No screenshot changes were required. Existing screenshots remain valid for the updated instructions and notes.

### Testing Notes

- **Testing Date**: 2026-06-04

### Testing Scope 

- End-to-end lab validation was completed successfully. Verified the updated Defender portal experience and validated all lab steps.

---
</details>

<details>
  <summary>2026-05-12</summary>

## Release Date: 2026-05-12

### Summary of Changes

Minor updates were applied to the lab guide to align with the latest Microsoft Defender portal UI changes.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated Microsoft Defender portal screenshots to reflect the latest UI experience and navigation changes.

### Testing Notes

- **Testing Date**: 2026-05-12

### Testing Scope 

- End-to-end lab validation was completed successfully. Verified the updated Defender portal experience and validated all lab steps.

---
</details>

<details>
  <summary>2026-04-15</summary>

## Release Date: 2026-04-15

### Summary of Changes

Minor enhancements were applied, such as incorporating the latest UI screenshots and refining instructions for better clarity and accuracy. 

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated the screenshots to align with the latest VS Code GitHub Copilot user interface.

### Testing Notes

- **Testing Date**: 2026-04-15

### Testing Scope 

- End-to-end lab testing was completed successfully with all validations passing, and the lab guide was updated to improve clarity and reflect the latest UI changes.

---
</details>




