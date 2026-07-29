  # Enterprise Knowledge Base Search and Query with Microsoft Foundry and Azure AI Search 

Welcome to the **Enterprise Knowledge Base Search and Query with Microsoft Foundry and Azure AI Search** Readme.md. On this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-07-28</summary>

## Release Date: 2026-07-28

### Summary of Changes

Updated the lab to use Microsoft Foundry instead of Azure OpenAI by revising Exercise 1 resource creation and model deployment steps, combining GPT and embedding model deployment into a single Deploy AI Models task, refreshing screenshots to match the latest Microsoft Foundry and Azure portal experience, and improving instructional clarity by explicitly identifying values learners must copy (resource name, API key, deployment names) for use in later exercises.

### Infrastructure Changes

- Replaced Azure OpenAI resource creation with Microsoft Foundry resource creation and provisioning steps.
- Combined GPT and embedding model deployment into a single Deploy AI Models task using Microsoft Foundry.
- Updated model deployment steps and portal navigation to follow the Microsoft Foundry workflow.
- Updated guidance on where to find and copy the API key, resource name, and deployment names in the portal.
- Updated the Json script inside the VM

### Content Changes

- Renamed the Lab name from # Enterprise Knowledge Base Search and Query with Azure OpenAI and Azure AI Search to # Enterprise Knowledge Base Search and Query with Microsoft Foundry and Azure AI Search.
- Rewrote Exercise 1 Task 1 to use the Microsoft Foundry provisioning workflow instead of Azure OpenAI.
- Consolidated GPT and embedding deployment instructions into one Deploy AI Models task and adjusted subsequent exercise references to those deployments.
- Updated references throughout the lab from “Azure OpenAI” to “Microsoft Foundry” where applicable.
- Clarified step text to explicitly call out values learners need to copy and reuse later (resource name, API key, deployment names).
- Refreshed and reworded steps to align with the Microsoft Foundry portal experience and to improve learner flow and clarity.
- Fixed spacing and formatting issues where found during the update pass.
  

### Screenshot Updates

  - Updated screenshots and step text to reflect Microsoft Foundry and the current Azure portal layout.
Exercise 1 (Provisioning & Model Deployment)

- Task 1 — Resource creation
  - Updated screenshots to show Microsoft Foundry resource creation screens and updated the corresponding instructions.

- Deploy AI Models — Combined deployment task
  - Added/updated screenshots showing the Deploy AI Models experience in Microsoft Foundry (model selection, deployment naming).
  - Updated instructions to match the combined deployment flow.

- API Key / Resource Values
  - Updated screenshots that show where to copy the resource name, API key, and deployment names; added guidance text to highlight these values for later exercises.

- Portal Navigation / Subscription Info
  - Updated screenshots to reflect current portal navigation (Microsoft Foundry entries) and blurred subscription group/ID where appropriate.

- Miscellaneous screenshots
  - Updated other exercise screenshots across the lab to match the current Azure portal and Microsoft Foundry UI so steps and visuals align.


### Testing Notes

- Validated the updated Exercise 1 provisioning and model deployment instructions against the Microsoft Foundry portal flow.
- Verified that the combined Deploy AI Models task covers both GPT and embedding deployment steps and that subsequent exercise references point to the combined deployments.
- Confirmed updated screenshots reflect the current Microsoft Foundry and Azure portal UI and that blurred/subscription-sensitive details were handled.
- Confirmed that values learners need to copy (resource name, API key, deployment names) are clearly identified and usable in later exercises.
- Reviewed markdown formatting and image rendering across the lab.

- **Testing Date:** 2026-07-28

### Testing Scope

---

</details>

<details>
  <summary>2026-06-29</summary>

## Release Date: 2026-06-29

### Summary of Changes

Updated the lab guide to align with the latest Azure portal experience by refreshing screenshots, improving instructional clarity, and adding a new **Resize the Virtual Machine View** section to enhance the learner experience. Updated the Azure OpenAI model from **GPT-4.1** to **GPT-5.4** as GPT-4.1 is scheduled for retirement in October.

### Infrastructure Changes

- Updated the Azure OpenAI model from **GPT-4.1** to **GPT-5.4**.
- Updated the lab instructions and screenshots to reflect the new model deployment.

### Content Changes

- Added a new **Resize the Virtual Machine View** section to the **Getting Started** page.
- Added a **Conclusion** section to the lab guide.
- Added emojis throughout the lab to improve readability and navigation.
- Fixed spacing and formatting issues across the lab guide.
- Updated the architecture diagram on the **Getting Started** page with the latest Azure AI service naming conventions.
- Updated Azure AI service naming conventions throughout the lab:
  - **Azure AI Search** *(formerly known as Cognitive Search)* → **AI Search (Foundry IQ)**
  - **Azure AI Document Intelligence** *(formerly known as Form Recognizer)* → **Document Intelligence**

### Screenshot Updates

#### Getting Started
- Added the **Resize the Virtual Machine View** section.

#### Lab 01
- **Task 1.2 – Point 3**
  - Updated the screenshot to reflect the **GPT-5.4** model.
  - Updated the corresponding instructions.
- **Task 3 – Point 6**
  - Updated the **Edit Template** screenshot with the latest model names.
  - Updated the corresponding instructions.
- **Task 3 – Point 9**
  - Updated the **Custom Deployment** screenshot with the latest model name.
  - Updated the corresponding instructions.
- **Task 3 – Point 12**
  - Updated the screenshot by blurring the subscription group and subscription ID.
- **Task 3 – Point 15**
  - Updated the Function App screenshot to include the new **AI (Preview)** option in the left navigation pane.

#### Lab 02
- **Task 1 – Point 3**
  - Updated the **Create Web App** screenshot to match the current Azure portal experience.
- **Task 2 – Point 1**
  - Updated the Web App screenshot to include the new **AI (Preview)** option in the left navigation pane.
- **Task 2 – Point 3**
  - Updated the Web App screenshot to include the new **AI (Preview)** option in the left navigation pane.
- **Task 3 – Point 4**
  - Updated the file upload screenshot.
- **Task 3 – Point 13**
  - Updated the file upload screenshot to match the latest Azure portal experience.
- **Task 3 – Point 16**
  - Updated the file upload screenshot to match the latest Azure portal experience.

### Testing Notes

- **Testing Date:** 2026-06-29

### Testing Scope

- Validated the updated instructions and screenshots across the lab.
- Verified the newly added **Resize the Virtual Machine View** section.
- Confirmed all updated screenshots reflect the latest Azure portal UI.
- Validated the complete lab flow end-to-end.
- Reviewed markdown formatting and image rendering.

---

</details>

<details>
  <summary>2026-06-16</summary>

## Release Date: 2026-06-16

### Summary of Changes

Updated the lab guide to align with the latest Azure portal experience by refreshing screenshots, improving instructional clarity, and adding new visual references to enhance the learner experience.

### Content Changes

- Updated instructions in **Exercise 1** and **Exercise 2** for improved clarity and consistency.
- Refined lab guidance to better align with the current Azure portal workflow.
- Added additional visual references to assist learners during resource navigation and configuration.

### Screenshot Updates

- **Labintro**:
  - Updated the screenshot (`g12-1.png`) with the Lab Guide experience and improved visual guidance.

- **Exercise 1 - Task 1.2**:
  - Updated the screenshot (`l12-12-05.png`) (`foundry-toggle.png`) (`feedbackpopup.png`) to align with the latest workflow.

- **Exercise 1 - Task 2.1**:
  - Updated the screenshot (`E1T2S1-2804.png`)  to reflect the latest Azure portal UI.

- **Exercise 1**:
  - Added a new screenshot (`page_02.png`) to improve navigation and visual clarity for learners

- **Exercise 2 - Task 1**:
  - Added a new screenshot (`database.png`) to provide additional guidance during database configuration.
  
- Improved screenshot placement and visual guidance throughout the lab.

### Testing Notes

- **Testing Date:** 2026-06-16

### Testing Scope

- Validated the updated instructions in Exercise 1 and Exercise 2.
- Verified all newly added and updated screenshots.
- Confirmed the lab flow aligns with the current Azure portal experience.
- Reviewed markdown formatting and image rendering.

---

</details>

<details>
  <summary>2026-05-29</summary>

## Release Date: 2026-05-29

### Summary of Changes

Updated the lab guide with the latest Azure portal UI screenshots, improved step clarity, and added additional guidance to help learners avoid deployment/configuration errors during lab execution.

### Content Changes

- Updated the **Exploring Your Lab Resources** screenshot on the Getting Started page with the latest UI.
- Removed the unnecessary colon from the **Lab Guide Zoom In/Zoom Out** instruction text.
- **Exercise 1 - Task 2.2**:
  - Updated the screenshot for **Document Intelligence** with the latest UI and improved step marking.
- **Exercise 1 - Task 2.3**:
  - Updated the screenshot for the **Translator resource** with the latest UI and improved step marking.
- **Exercise 2 - Task 1**:
  - Added an additional note for image and tag naming to help avoid errors during the lab.

### Screenshot Updates

- Refreshed Azure portal screenshots to align with the latest Azure UI experience.
- Improved screenshot annotations and step highlighting for better learner understanding.

### Testing Notes

- **Testing Date**: 2026-05-29

### Testing Scope 

- Validated the updated instructions and screenshots.
- Verified the lab flow and notes for better learner experience and clarity.

---
</details>

<details>
  <summary>2026-04-28</summary>

## Release Date: 2026-04-28

### Summary of Changes

Updated the lab guide with formatting improvements, Azure portal UI updates, clearer instructions, and infrastructure template refinements. 

### Infrastructure Changes

- Updated the psscript to use the CloudLabs `Download` function command for file downloads.
- Updated the deployment template in **Exercise 1 - Task 3**:
  - Changed the model deployment to **gpt-4.1**
  - Updated the deployment type to **Chat**
  - Updated the **Document Intelligence** deployment value as the previous configuration was using the older endpoint format, which was causing authentication/connection failures.

### Content Changes

- Updated Task and Exercise heading sizes as per the quality checklist recommendations.
- Removed MFA-related steps from the **Getting Started** page as they are no longer required.
- **Exercise 1**:
  - Added numbered subheadings for tasks (for example: Task 1.1, Task 1.2, etc.)
  - Updated steps and notes for better clarity and understanding.
- **Exercise 2**:
  - Updated steps and notes for improved clarity and understanding.

### Screenshot Updates

- Updated Azure portal screenshots to reflect the latest minor UI changes.
- Refreshed screenshots in **Exercise 1 and 2** to align with the updated Azure portal experience.

### Testing Notes

- **Testing Date**: 2026-04-28

### Testing Scope 

- Performed end-to-end lab validation and verified all exercises, deployments, and instructions successfully.

---
</details>


<details>
  <summary>2025-10-27</summary>

## Release Date: 2025-10-27

### Summary of Changes

Minor updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.   

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced screenshots to match the latest user interface.

### Testing Notes

- **Testing Date**: 2025-10-27

### Testing Scope 

- Performed end to end lab testing, and all validations were successful. Updated the lab guide for better clarity.

---
</details>

<details>
  <summary>2025-09-15</summary>

## Release Date: 2025-09-15

### Summary of Changes

Minor updates, including clearer UI screenshots and refined instructions for improved clarity and accuracy.   

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced screenshots to match the latest user interface.
    
### Testing Notes

- **Testing Date**: 2025-09-15

### Testing Scope 

- Performed end to end lab testing, and all validations were successful. Updated the lab guide for better clarity.

---
</details>

<details>
  <summary>2025-05-23</summary>

## Infrastructure Changes

NA

## Content Changes

- **Change**:

    1. Updated the lab guide according to the UI changes in the Azure AI foundry portal, with the Rebranding of Azure OpenAI Studio to AI foundry
    2. Updated the template that is being within the lab with new deployment names of the GPT models.
  
## Screenshot Updates

- **Change**: 

    1. Screenshots have been updated as per new UI changes and updated instructions
    2. Getting started page has been updated as per the new UI changes in the CloudLabs

## Testing Notes

- **Testing Date**: 2025-05-22

---
</details>
