# Business Automation with Azure OpenAI and Document Intelligence

Welcome to the **Business Automation with Azure OpenAI and Document Intelligence** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-09-09</summary>

## Release Date: 2026-09-09

### Summary of Changes

Updated Lab 2 to replace the deprecated Azure OpenAI Bring Your Own Data workflow with the new Microsoft Foundry with Your Own Data experience.

### Infrastructure Changes

- Updated the Microsoft Foundry ARM template to support the new Foundry project configuration and automated role assignments.
- Resolved the Foundry project deployment issue by updating the Azure AI Services configuration.
- Validated GPT-5.4-mini and embedding model deployments.
- Configured and verified automated RBAC assignments for Microsoft Foundry and Azure AI Search.

### Content Changes

- Updated Lab 2 to use Microsoft Foundry, Foundry IQ, knowledge sources, knowledge bases, and Foundry Agents.
- Updated the lab tasks and instructions to reflect the current Microsoft Foundry portal experience.
- Updated the workshop presentation to replace the deprecated Bring Your Own Data content with the new Microsoft Foundry workflow.

### Screenshot Updates

- Updated Lab 2 screenshots to reflect the current Microsoft Foundry experience.
- Added updated screenshots for knowledge source, knowledge base, and Foundry Agent configuration.

### Testing Notes

- **Testing Date**: 2026-09-03

### Testing Scope

- Completed end-to-end testing of the entire hands-on lab.
- Validated Exercise 1, including Azure AI Document Intelligence resource creation, custom model training, BPA pipeline configuration, managed identity access, and Azure AI Search configuration.
- Validated Exercise 2, including Microsoft Foundry navigation, File knowledge source and knowledge base creation, Foundry Agent configuration, and interaction with the uploaded Porsche manual.
- Validated the updated Microsoft Foundry and Foundry IQ workflow.
- Verified GPT-5.4-mini and embedding model deployments.
- Verified Microsoft Foundry and Azure AI Search RBAC configuration.
- Validated the updated ARM template deployment and automated role assignments.

</details>

<details>
  <summary>2026-05-27</summary>

## Release Date: 2026-05-27

### Summary of Changes

- Lab guides have been thoroughly reviewed and updated for improved clarity, enhanced security practices, and alignment with current Azure portal UI. New comprehensive lab scenario sections added for better context and engagement.

### Infrastructure Changes

- NA

### Content Changes

- **Lab Scenarios**: Added comprehensive scenario descriptions to Lab 1, Lab 2, and Getting Started pages for better context and learner engagement.
- **Lab 1 - Task 1**: Enhanced sign-in instructions with improved clarity, visual callouts, and better image descriptions.
- **Lab 1 - Task 2**: Updated step numbering and formatting for improved navigation and visual clarity.
- **Lab 1 - NEW Task 4**: "Configure Managed Identity Access for Azure AI Search" - Comprehensive new task with 6 steps and supporting screenshots. Implements secure RBAC-based access for Azure AI Search managed identity to Azure Storage, replacing insecure connection string authentication.
- **Lab 1 - Task 5** (formerly Task 4): "Configure Azure AI Search" - Completely refactored with 11 detailed steps and 7 new screenshots. Enhanced field configuration workflow with new `azureblob_index` field setup and expanded Organization field facetable settings.
- **Lab 1 - Task 6** (formerly Task 5): Renumbered "Use Sample Search Application [Read Only]".
- **Screenshot Updates**: 16 new images added, 7 existing images updated to reflect current Azure Portal UI.
- **Lab 2**: Added comprehensive lab scenario for context.

### Screenshot Update

- 16 new screenshots added to capture new Managed Identity configuration workflow.
- 7 existing screenshots updated to reflect latest Azure portal interface and UI changes.

### Security Improvements

- Implemented Azure Role-Based Access Control (RBAC) for Azure AI Search managed identity instead of connection string-based authentication.
- Storage Blob Data Reader role assignment provides secure, least-privilege access to storage resources.

### Testing Notes

- **Testing Date**: 2026-05-27
- **Testing Scope**: End-to-end lab testing completed. All tasks validated sequentially. Screenshots verified against current Azure Portal UI. Lab flow and security configurations confirmed.
-------------

</details>

<details>
  <summary>2026-01-19</summary>
 
## Release Date: 2026-01-19
 
### Summary of Changes
 
- The lab has been successfully tested, and the lab content along with validations have been reviewed and updated.
### Infrastructure Changes
 
- NA
 
### Content Changes
 
- Few instructions has been updated for better understanding
 
### Screenshot Update
 
- Updated few screenshots according to the instructions to improve the overall experience.
 
### Testing Notes
 
- **Testing Date**: 2026-01-19
 
### Testing Scope
 
- Performed end to end lab testing and all validations were successful, updated lab guide for better clarity.
 
-------------
 
</details>


<details>
  <summary>2026-01-06</summary>
 
## Release Date: 2026-01-06
 
### Summary of Changes
 
-  Updated the guide with clearer, up-to-date UI screenshots and refined instructions for improved clarity.
 
### Infrastructure Changes
 
- NA
 
### Content Changes
 
- NA
 
### Screenshot Update
 
- Updated screenshots to enhance clarity in the instructions and improve the overall experience.
 
### Testing Notes
 
- **Testing Date**: 2026-01-06
 
### Testing Scope
 
- Validation included infrastructure compatibility, lab flow continuity, content accuracy, and screenshot alignment with the latest UI.
 
-------------
 
</details>


<details>
  <summary>2025-12-23</summary>
 
## Release Date: 2025-12-23
 
### Summary of Changes
 
-  Updated the guide with clearer, up-to-date UI screenshots and refined instructions for improved clarity.
 
### Infrastructure Changes
 
- NA
 
### Content Changes
 
- NA
 
### Screenshot Update
 
- Updated screenshots to enhance clarity in the instructions and improve the overall experience.
 
### Testing Notes
 
- **Testing Date**: 2025-12-23
 
### Testing Scope
 
- Validation included infrastructure compatibility, lab flow continuity, content accuracy, and screenshot alignment with the latest UI.
 
-------------
 
</details>

<details>
  <summary>2025-12-10</summary>
 
## Release Date: 2025-12-10
 
### Summary of Changes
 
-  Updated the guide with clearer, up-to-date UI screenshots and refined instructions for improved clarity.
 
### Infrastructure Changes
 
- NA
 
### Content Changes
 
- Updated the Azure OpenAI model used in the lab from gpt-35-turbo to gpt-4.1-mini.
 
### Screenshot Update
 
- Updated several screenshots to enhance clarity in the instructions and improve the overall experience.
 
### Testing Notes
 
- **Testing Date**: 2025-12-10
 
### Testing Scope
 
- Validation included infrastructure compatibility, lab flow continuity, content accuracy, and screenshot alignment with the latest UI.
 
-------------
 
</details>

<details>
  <summary>2025-10-10</summary>

## Release Date: 2025-10-10

### Summary of Changes

- The lab has been successfully tested, and the lab content along with validations have been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-10-10

### Testing Scope 

- Performed end to end lab testing and all validations were successful, updated lab guide for better clarity.

</details>

<details>
  <summary>2025-09-10</summary>

## Release Date: 2025-09-10

### Summary of Changes

- The lab has been successfully tested, and the lab content along with validations have been reviewed and updated.

### Testing Notes

- **Testing Date**: 2025-09-10

### Testing Scope 

- Performed end to end lab testing and all validations were successful, updated lab guide for better clarity.

</details>

<details>
  <summary>2025-09-02</summary>

## Release Date: 2025-09-02

## Summary of Changes
- Minor updates with clearer UI screenshots, refined instructions, and added validations for accuracy.

## Infrastructure Changes

NA

## Content Changes

- **Minor Changes**: Updated instructions and screenshots in the lab to align with the recent CloudLabs UI updates.
  
## Screenshot Updates

- **Change**: The screenshots are updated, which has old name branding, lab content and Cloudlabs UI.

## Testing Notes

- **Testing Date**: 2025-08-29
- **Resolved Issues**: NA

## Testng Scope

- Completed end-to-end testing, validated lab implementation, and confirmed successful checks across RBAC, policy, negative testing, cost estimate updates, and calendar.
  
</details>

<details>
  <summary>2025-07-09</summary>

## Infrastructure Changes

NA

## Content Changes

- **Major Changes**: 
    - Relevant content sections have been reviewed and updated for accuracy and clarity.

- **Minor Changes**: Updated instructions and UI elements to reflect recent changes in the Azure portal.
  
## Screenshot Updates

- **Change**: The screenshots are updated, which are unclear.

## Testing Notes

- **Testing Date**: 2025-07-09
- **Resolved Issues**: NA
</details>

<details>
  <summary>2025-06-18</summary>

## Infrastructure Changes

NA

## Content Changes

- **Major Changes**: 
    - * The architecture diagram image was updated to better align with the overall content.

- **Minor Changes**: Minor UI Changes and instructions updated.
  
## Screenshot Updates

- **Change**: The screenshots have been updated to reflect the latest interface.

## Testing Notes

- **Testing Date**: 2025-06-18
---
</details>

<details>
  <summary>2025-05-23</summary>

## Infrastructure Changes

NA

## Content Changes

- **Major Changes**:
  - Updated navigation and instruction flow to reflect recent Azure UI changes.
  - Adjusted references and steps to align with the latest interface layout for a smoother user experience.

- **Minor Changes**: Minor updates made to the UI references and corresponding instructions.
  
## Screenshot Updates

NA

## Testing Notes

- **Testing Date**: 2025-05-22
---
</details>


<details>
  <summary>2025-05-16</summary>

## Infrastructure Changes

NA

## Content Changes

- **Change**: Minor UI Changes and instructions updated.

## Screenshot Updates

- **Change**: Screenshots are upto date.

## Testing Notes

- **Testing Date**: 2025-05-15

---
</details>


<details>
  <summary>2024-12-31</summary>

## Infrastructure Changes

NA

## Content Changes

- Major Updates 

  - Updated configuration for Function Apps to enhance overall functionality.

- Minor Updates 

  - Updated all references from **Azure OpenAI Studio** to the newly rebranded **Azure AI Foundry Portal**.
  - Updated **Cognitive Search** to the new **AI Search**, aligning with the latest platform changes.


## Screenshot Updates

- **Change**: Screenshots are upto date.

## Testing Notes

- **Testing Date**: 2024-12-31

---
</details>


  





