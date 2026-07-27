# Azure AI Gateway: API Management for Intelligent Services

Welcome to the  **Azure AI Gateway: API Management for Intelligent Services** Release-Notes.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

 `For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-07-18</summary>

## Release Date: 2026-07-18

### Summary of Changes

This release updates the lab guide to align with the latest Microsoft Foundry experience. Exercise 5 has been redesigned to use the new Guardrails workflow, replacing the deprecated Content Filters experience. The lab now demonstrates a centralized Guardrails-based approach for validating content safety through the Chat Playground, Python, and Azure API Management. Additionally, screenshots and notebook validation outputs have been refreshed across the lab.

### Infrastructure Changes

- N/A

### Content Changes

- Exercises 1–4
  - Added expected notebook initialization output screenshots to help learners verify successful execution.
  - Replaced blurry screenshots with updated, high-quality images.
- Exercise 5
  - Migrated from the deprecated Content Filters / Guardrails + Controls workflow to the new Microsoft Foundry Guardrails experience in the new Foundry portal.
  - Updated the lab to create and configure a reusable Guardrail instead of separate content filters.
  - Added instructions to validate Guardrails using the Chat Playground with scenarios covering harmful content, jailbreak attempts, prompt injection, protected materials, and PII.
  - Updated Python validation to reuse the configured Guardrail instead of creating request-time content filters.
  - Updated portal navigation, lab instructions, prompts, and screenshots to match the latest Microsoft Foundry UI and workflow.

### Screenshot Updates

- Updated screenshots throughout Exercises 1–5 to reflect the latest Microsoft Foundry portal.
- Added notebook initialization output screenshots for Exercises 1–4.
- Replaced outdated and low-quality screenshots with current UI images.
- Updated screenshots for the new Guardrails configuration, validation workflow, and APIM content safety testing.

### Testing Notes

- **Testing Date:** 2026-07-17

### Testing Scope

- Validated the lab end-to-end using the updated Microsoft Foundry experience.
- Verified the new Guardrails workflow in Ex 5, including creation, configuration, Chat Playground validation, Python-based validation, and Azure API Management integration.
- Confirmed that all updated instructions, navigation steps, and screenshots accurately reflect the current Microsoft Foundry portal experience.

---
</details>

<details>
  <summary>2026-06-29</summary>

## Release Date: 2026-06-29

### Summary of Changes

This release updates the lab to use the latest supported GPT-5 family models in Microsoft Foundry. Deprecated models have been replaced to ensure continued compatibility with the latest Azure AI offerings and to prevent disruptions caused by upcoming model retirements.

### Infrastructure Changes

- Updated Azure AI model deployments to use the latest supported GPT-5 family models.

### Content Changes

Replaced deprecated model references throughout the lab guide.

- Removed references to **gpt-4o-mini**, **gpt-4.1-mini**, **gpt-4.1**, **o4-mini**, and **deepseek-r1**.
- Added references to **gpt-5**, **gpt-5.1**, **gpt-5-mini**, and **gpt-5-nano**.
- Updated deployment instructions to align with the latest Microsoft Foundry supported models.

### Screenshot Updates

- Updated screenshots to reflect the latest GPT-5 model selections and Microsoft Foundry deployment experience, where applicable.

### Testing Notes

- **Testing Date:** 2026-06-29

### Testing Scope

Validated all model deployments using the updated GPT-5 family models, verified end-to-end lab functionality, and confirmed that the updated instructions and model references work as expected with the current Microsoft Foundry experience.

---
</details>

<details>
  <summary>2026-06-08</summary>

## Release Date: 2026-06-08

### Summary of Changes

 This includes updates to align the lab guide with the latest Azure and Microsoft Foundry portal experience. The changes focus on improving learner guidance, updating UI references, refreshing screenshots, and enhancing overall clarity and usability.

### Infrastructure Changes

N/A

### Content Changes

- Added exercise scenarios and contextual information to the Getting Started page and lab exercises.
- Updated instructions to reflect the latest Azure and Microsoft Foundry portal workflows.
- Refined zoom in/out guidance based on the current portal experience.
- Added a note to guide learners when redirected to the new Microsoft Foundry portal, including steps to switch back to the classic experience when required.
- Added guidance for handling portal pop-ups that may appear during lab execution.
- Improved instructional clarity and consistency throughout the lab guide.

### Screenshot Updates

- **Updated Screenshots:** Refreshed environment and split-window screenshots to reflect the latest Azure and Microsoft Foundry UI.
- **New Screenshots:** Added screenshots supporting the updated Foundry portal navigation and redirection guidance.

### Testing Notes

- **Testing Date:** 2026-06-08

### Testing Scope

Conducted end-to-end validation of the lab guide, verified all updated instructions and screenshots, confirmed step sequencing, validated portal workflows, and ensured alignment with the current Azure and Microsoft Foundry user experience.

---
</details>
<details>
  <summary>2026-04-27</summary>

## Release Date: 2026-04-27

### Summary of Changes

Minor updates have been made, including UI updates, refreshed screenshots, and refined instructions to improve clarity and accuracy.

### Infrastructure Changes

N/A

### Content Changes

- Exercise 1 Task 1 step 17 : New note added with 2 new screenshots to make instructions clearer.
- Exercise 4 Task 2 step 6 : New note added with 2 new related screenshots for better understanding of steps mentioned in the note.
- Exercise 5 Task 3 step 8: screenshot changed due to updates in the code.

 
### Screenshot Updates

- **Updated Screenshots**: The screenshots have been updated to better illustrate and clarify the steps described.
      
### Testing Notes

- **Testing Date**: 2026-04-27

### Testing Scope 

Conducted end-to-end testing, validated the lab guide steps, enhanced the labguide with new latest screenshots and added instructions for better clarity.

---
</details>

<details>
  <summary>2026-01-14</summary>

## Release Date: 2026-01-14

### Summary of Changes

Minor updates have been made, including UI updates, refreshed screenshots, and refined instructions to improve clarity and accuracy.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Updated Screenshots**: Updated screenshots with respective instructions.
      
### Testing Notes

- **Testing Date**: 2026-01-14

### Testing Scope 

Conducted end-to-end testing, validated the lab guide steps, enhanced the labguide with new latest screenshots and added instructions for better clarity.

---
</details>
