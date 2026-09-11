# Developing a Custom RAG App Using Microsoft Foundry

Welcome to the  **Developing a Custom RAG App Using Microsoft Foundry** Release-Notes.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

 `For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-09-11</summary>

## Release Date: 2026-09-11

### Summary of Changes

Updated the **Developing a Custom RAG App Using Microsoft Foundry** lab to align with the latest Microsoft Foundry experience and terminology. The lab now uses the hub-less Foundry resource workflow, **gpt-5-mini**, **AI Search (Foundry IQ)**, updated Microsoft Foundry SDK packages, refreshed telemetry instructions, and ASSERT-based evaluation and regression testing.

### Infrastructure Changes

* Updated the Microsoft Foundry provisioning workflow to create a **Microsoft Foundry resource and default project directly from the Azure portal**, removing the requirement to provision a separate AI Hub.
* Updated the chat model from **gpt-4.1-mini** to **gpt-5-mini**.
* Updated model configuration to use **gpt-5-mini** for chat, evaluation, and intent-mapping workloads.
* Updated the required Microsoft Foundry SDK package versions:

  * `azure-ai-projects==1.0.0b11`
  * `azure-ai-inference[prompts]==1.0.0b9`
* Added ASSERT framework dependencies and configuration required for spec-driven RAG evaluation.

### Content Changes

* **Lab Overview and Architecture**

  * Updated terminology from **Azure AI Search** to **AI Search (Foundry IQ)** throughout the lab.
  * Updated architecture and component descriptions to reflect Microsoft Foundry, AI Search (Foundry IQ), AI models, and the revised RAG workflow.
  * Refined the repository structure description to provide a simplified folder-level view of the sample repository.

* **Exercise 1 - Developing a Custom RAG App Using Microsoft Foundry**

  * Replaced the AI Hub-based setup with the current **Microsoft Foundry resource and project** provisioning workflow.
  * Updated model deployment instructions to use **gpt-5-mini** and `text-embedding-ada-002`.
  * Updated model rate-limit configuration to use **30,000 Tokens per Minute**.
  * Updated **AI Search (Foundry IQ)** creation and connection instructions to align with the current Foundry experience.
  * Added instructions to retrieve the AI Search endpoint and primary admin key for application configuration.
  * Updated the development setup with the required Microsoft Foundry SDK package versions.
  * Updated `.env` configuration to use `PROJECT_ENDPOINT`, `SEARCH_ENDPOINT`, `SEARCH_KEY`, and **gpt-5-mini** for chat, evaluation, and intent mapping.

* **Exercise 2 - Build a Retrieval-Augmented Generation (RAG) Pipeline**

  * Refreshed prompt-template guidance for the retrieval and grounded-response workflows.
  * Updated the telemetry workflow to instruct learners to switch **New Foundry** off and use the classic Microsoft Foundry experience for Application Insights tracing,as its not completely available in new portal.
  * Added guidance for handling the optional Foundry feedback prompt.
  * Refined the telemetry instructions for generating, refreshing, reviewing, and filtering traces in Microsoft Foundry.

* **Exercise 3 - Evaluate and Optimize RAG Performance with ASSERT**

  * Expanded the evaluation workflow to introduce **ASSERT (Adaptive Spec-driven Scoring for Evaluation and Regression Testing)**.
  * Added instructions to install and configure ASSERT using the deployed **gpt-5-mini** model.
  * Added configuration for Azure OpenAI endpoint and authentication values required by ASSERT.
  * Added `assert_target.py` as the wrapper for invoking the existing RAG application during evaluation.
  * Added `eval_config.yaml` to define grounding, domain, safety, and expected assistant behaviors.
  * Added instructions to execute spec-driven evaluation using:
    `assert-ai run --config eval_config.yaml`
  * Added guidance for reviewing ASSERT-generated test cases and scored evaluation artifacts.
  * Retained Azure AI Evaluation metrics for **Groundedness, Relevance, and Coherence** alongside the ASSERT workflow.
  * Updated the prompt-improvement workflow to re-run ASSERT after modifying `grounded_chat.prompty`.
  * Added baseline comparison guidance to validate improvements and use ASSERT as a regression check.

### Screenshot Updates

- Refreshed screenshots across the lab to align with the latest Microsoft Foundry portal experience and updated service terminology.
- Updated visuals for Microsoft Foundry resource creation, model deployment, AI Search (Foundry IQ) configuration, and environment setup.
- Refreshed RAG pipeline and telemetry screenshots to reflect the current Visual Studio Code and Microsoft Foundry workflows.
- Added and updated screenshots for the ASSERT evaluation workflow, including configuration, execution, result review, and prompt optimization.
- Updated supporting screenshots wherever navigation, labels, or UI elements changed.

### Testing Notes

- **Testing Date**: 2026-09-10

### Testing Scope

* Microsoft Foundry resource and project provisioning
* AI model deployment and configuration
* AI Search (Foundry IQ) provisioning and integration
* Microsoft Foundry SDK dependency installation
* RAG indexing, retrieval, and response generation
* Application Insights telemetry and tracing
* Azure AI Evaluation metrics
* ASSERT spec-driven evaluation
* Prompt optimization and regression validation

</details>

<details>
  <summary>2026-04-22</summary>

## Release Date: 2026-04-22

### Summary of Changes

Enhanced the overall lab experience by updating UI screenshots to reflect the latest interface and improving step-by-step instructions for better clarity and usability.

### Infrastructure Changes

- Added automation to clone the latest lab repository from GitHub (azureai-samples) during VM provisioning.
- Implemented retry logic (3 attempts) to validate Python installation and ensure availability before proceeding with subsequent steps.
- Included step to upgrade pip using the explicitly defined Python path to maintain compatibility with latest packages.

### Content Changes

- Enhanced the Getting Started page with clearer instructions, including the lab scenario, validation checks, prerequisites, and repository structure.
- Refined all lab exercises to incorporate detailed scenarios, improved summaries, and more structured, easy-to-follow instructions.
- Added the complete working version of `evaluate.py` for reference after users update the file to include coherence and relevance evaluators.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI and model configuration:
- Updated the architecture diagram on the Getting Started page to visually represent each lab exercise with clearly defined sections.
  
### Testing Notes

- **Testing Date**: 2026-04-22

### Testing Scope 

Performed end-to-end validation of all labs to ensure accuracy and usability. Verified updated instructions and tested deployment workflows using the working model configuration. Also ensured that all updated screenshots align with the current UI and documented steps.

---
</details>

<details>
  <summary>2026-04-14</summary>

## Release Date: 2026-04-14

### Summary of Changes

Enhanced the overall lab experience by updating UI screenshots to reflect the latest interface and improving step-by-step instructions for better clarity and usability. Additionally, updated the model to gpt-4.1-mini to support the evaluation workflow.

### Infrastructure Changes

N/A

### Content Changes

- Improved and clarified instructions in Getting started page and Lab 1 to make the steps easier to follow for users.
- Updated Lab 1 to use gpt-4.1-mini model to support the evaluation workflow.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI and model configuration:
- Updated the Getting started page and Lab 01 page screenshots to reflect the current interface.

### Testing Notes

- **Testing Date**: 2026-04-14

### Testing Scope 

Performed end-to-end validation of all labs to ensure accuracy and usability. Verified updated instructions, confirmed correct model replacement in Azure AI Foundry, and tested deployment workflows using the latest model configuration. Also ensured that all updated screenshots align with the current UI and documented steps.

---
</details>

<details>
  <summary>2026-04-10</summary>

## Release Date: 2026-04-10

### Summary of Changes

Enhanced the overall lab experience by updating UI screenshots to reflect the latest interface and improving step-by-step instructions for better clarity and usability. Additionally, replaced the deprecated GPT-4.1 Mini model with GPT-5 Mini to ensure continued compatibility and alignment with upcoming model support changes.

### Infrastructure Changes

N/A

### Content Changes

- Improved and clarified instructions in Lab 1 and Lab 3 to make the steps easier to follow for users.
- Added detailed guidance for model replacement to support the transition from GPT-4.1 Mini to GPT-5 Mini.
- Refined instructional content to reduce ambiguity and improve the overall learning experience.

### Screenshot Updates

Screenshots have been updated to reflect the latest UI and model configuration:
- Updated the Lab 01 page screenshots to showcase the new model (GPT-5 Mini) and current interface.

### Testing Notes

- **Testing Date**: 2026-04-10

### Testing Scope 

Performed end-to-end validation of all labs to ensure accuracy and usability. Verified updated instructions, confirmed correct model replacement in Azure AI Foundry, and tested deployment workflows using the latest model configuration. Also ensured that all updated screenshots align with the current UI and documented steps.

---
</details>

<details>
  <summary>2026-01-06</summary>

## Release Date: 2026-01-06

### Summary of Changes

Updated the guide with clearer, up-to-date UI screenshots and refined instructions for improved clarity.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- Updated screenshots to enhance clarity in the instructions and improve the overall experience.
      
### Testing Notes

- **Testing Date**: 2026-01-06

### Testing Scope 

Performed end-to-end lab testing and validations, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-11-21</summary>

## Release Date: 2025-11-21

### Summary of Changes

Made updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity.  

### Infrastructure Changes

N/A

### Content Changes

- Instructions updated as per UI updates in Azure AI Foundry (Microsoft Foundry) Portal. 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated screenshots as per the new UI. 
      
### Testing Notes

- **Testing Date**: 2025-11-20

### Testing Scope 

Performed end-to-end lab testing and validations, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-10-23</summary>

## Release Date: 2025-10-23

### Summary of Changes

Made updates by adding clearer, up-to-date UI screenshots and refining instructions to enhance clarity.  

### Infrastructure Changes

N/A

### Content Changes

- GPT model updated from gpt-4o-mini to gpt-4.1-mini as gpt-4o-mini is getting retired. 

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Updated screenshots for clarity. 
      
### Testing Notes

- **Testing Date**: 2025-10-23

### Testing Scope 

Performed end to end lab testing and validtions, updating instructions and screenshots. 

---
</details>

<details>
  <summary>2025-06-12</summary>

### Release Date: 2025-05-16

- **Testing Date**: 2025-06-12

## Infrastructure Changes

NA

## Content Changes

**Change**: Incorporated recent updates from Azure AI Foundry and updated the corresponding screenshots accordingly.

#### Lab 1

-  Implemented a new approach to create the AI Hub. Currently building the AI Hub via the Azure portal,from their launching the AI Foundry.

## Screenshot Updates

- **Change**: Screenshots have been updated to align with the revised task execution process

## Testing Notes

- **Test Validation Summary**: Validated the lab guide steps, updated the content to reflect the latest UI changes.


---
</details>
