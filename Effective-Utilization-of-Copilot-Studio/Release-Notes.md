# Effective Utilization of Copilot Studio 

Welcome to the **Effective Utilization of Copilot Studio** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes
<details>
  <summary>2026-08-18</summary>

## Release Date: 2026-08-18

### Summary of Changes

Updated instructions across the Overview/Login page and Labs 02–05 to align with the current Copilot Studio experience (Classic UI, renamed tabs, updated system topic behavior). Corrected agent orchestration settings, fixed an incorrect assumption about the Fallback topic's structure, replaced an unreliable UI-dependent step in the Monitoring task, and added missing context/setup steps flagged during content review to improve reproducibility and clarity for learners.

### Infrastructure Changes

N/A

## Content Changes

**Overview / Login Page**
* Added explicit steps to switch from the **New experience** to the **Old (Classic) experience** immediately after sign-in. Old UI experience is required since Topics, conditions, entities, and tool nodes used throughout Labs 02–05 don't exist in the new experience.
* Added a note clarifying that seeing **Start Free Trial** instead of **Get Started** indicates a missing license assignment, with guidance to contact CloudLabs support.
* Added a **Resize the Virtual Machine View** section describing the slider control between the VM and Lab Guide panes.

**Lab 02: Build your own Agent**
* Task 2: Removed the instruction to manually repeat steps for the USA condition node; replaced with an explanation that Copilot Studio auto-generates a condition branch for each option (India/USA) added in the prior step.
* Task 5: Renamed all "Analytics" references to **Monitor** (current tab name). Rebuilt the task around the actual, always-available dashboard sections: Overview tile (Conversation sessions, Total reactions, Engagement), Effectiveness - Conversation outcomes chart, and Reactions/Sentiment - replacing reliance on the inconsistent "Expose your agent's value!" popup. Added a note explaining why Generated answer rate/quality and Knowledge source use remain empty for this agent.

**Lab 03: Create a Conversational Design**
* Task 2: Added a verification step ("The updated topic flow should look like this") with reference screenshots before testing, so learners can confirm their build matches the expected flow before troubleshooting.
* Minor instructional clarity fix: explicitly noting to close the Create generative answers properties box after verifying the configured message.

**Lab 04: Copilot Studio with Data and Generative AI**
* Task 1: Added a required setup step immediately after `webagent` creation to **disable Generative AI orchestration (set to Classic)** and set the **Model to GPT-5 Chat**. This ensures Conversational Boosting and Fallback behave consistently and as scripted for every learner, rather than being intermittently bypassed under Generative AI orchestration.
* Task 1: Added explanatory context after the first Conversational Boosting test, clarifying that the initial unformatted response reflects default behavior before customization.
* Task 1: Corrected an inaccurate description of the **Fallback** topic; it does not contain a generative answers node; it's a fully deterministic flow (FallbackCount condition → static message → Escalate topic). Instructions rewritten to reflect this.
* Task 1: Added a note clarifying that live-agent escalation is not configured in this lab environment, so a placeholder/default response is expected instead of an actual handoff.
* Task 2 (HR-Agent): Replaced a vague "review Generative AI settings" step with an explicit instruction confirming **Generative AI orchestration must remain set to Yes** for this agent, since it depends on generative orchestration to answer from the uploaded document.

**Lab 05: Tools in Copilot Studio**
* Task 1: Changed the recommended entity from "Country or region" to **City**, which the weather connector resolves more reliably.
* Task 1: Added an explicit connection-naming step for clarity during connector setup.
* Task 1: Added an explicit test prompt ("What is the weather today?") instead of an open-ended testing instruction.
* Task 2: Added an explicit test prompt ("Hi, can you give me the weather updates?") for the plugin-calling test step.

### Screenshot Updates

* Refreshed screenshots across the Login/Overview page and Labs 02–05 to align with the current Copilot Studio UI (Classic experience), including the Monitor tab layout, Generative AI settings pages, and the corrected Fallback topic flow.
* Replaced outdated screenshots that referenced the old "Analytics" tab, incorrect Fallback node structure, and prior variable/condition configurations no longer matching current agent behavior.

### Testing Notes

- **Testing Date**: 2026-08-18

### Testing Scope

Performed end-to-end validation of the Overview/Login page and Labs 02–05, agent orchestration settings (Classic for `webagent`/`Weather`, Generative AI enabled for `HR-Agent`), Monitor tab metrics, Fallback topic behavior, and tool/connector configuration steps all align with the current Copilot Studio UI and produce consistent, reproducible outcomes.

---
</details>


<details>
  <summary>2026-07-20</summary>

## Release Date: 2026-07-20

### Summary of Changes

Updated screenshots and related instructions to align with the latest Copilot Studio experience. Corrected agent names, variable references, and condition configurations to improve accuracy and ensure consistency throughout the guide.

### Infrastructure Changes

N/A

### Content Changes

- Updated screenshots and instructions to reflect the latest UI changes.
- Corrected agent names and variable references where required.
- Updated condition configurations to match the current experience.
- Improved instructional accuracy and overall learner experience.

### Screenshot Updates

- Refreshed screenshots to align with the latest Copilot Studio UI.
- Replaced outdated screenshots containing incorrect agent names, variable references, and condition options.

### Testing Notes

- **Testing Date**: 2026-07-20

### Testing Scope

Performed end-to-end validation of the affected sections and verified that all updated screenshots and instructions align with the current UI experience.

---
</details>

<details>
  <summary>2026-06-17</summary>

## Release Date: 2026-06-17

### Summary of Changes

Updated screenshots and related instructions to align with the latest Copilot Studio experience. Corrected agent names, variable references, and condition configurations to improve accuracy and ensure consistency throughout the guide.

### Infrastructure Changes

N/A

### Content Changes

- Updated screenshots and instructions to reflect the latest UI changes.
- Corrected agent names and variable references where required.
- Updated condition configurations to match the current experience.
- Improved instructional accuracy and overall learner experience.

### Screenshot Updates

- Refreshed screenshots to align with the latest Copilot Studio UI.
- Replaced outdated screenshots containing incorrect agent names, variable references, and condition options.

### Testing Notes

- **Testing Date**: 2026-06-17

### Testing Scope

Performed end-to-end validation of the affected sections and verified that all updated screenshots and instructions align with the current UI experience.

---
</details>

<details>
  <summary>2026-06-04</summary>

## Release Date: 2026-06-04

### Summary of Changes

Updated all labs to align with the latest agent creation experience and improved the overall guide. Added Scenario sections and updated Overview content across labs for better understanding. Also refreshed screenshots and corrected rendering issues.

### Infrastructure Changes

N/A

### Content Changes

- Several screenshots and corresponding lab guide instructions were updated to improve clarity and enhance the overall user experience.

- Refined wording and instructional clarity in multiple steps throughout the labs.

### Screenshot Updates

- Updated screenshots across all labs to match the latest Copilot Studio experience.
- Replaced outdated or blurred images with clearer screenshots.
      
### Testing Notes

- **Testing Date**: 2026-06-04

### Testing Scope 

Performed end-to-end validation of the lab, ensuring all steps work as expected. Updated the lab guide with clear and accurate instructions.

---
</details>

<details>
  <summary>2026-05-22</summary>

## Release Date: 2026-05-22

### Summary of Changes

Updated all labs to align with the latest agent creation experience and improved the overall guide. Added Scenario sections and updated Overview content across labs for better understanding. Also refreshed screenshots and corrected rendering issues.

### Infrastructure Changes

N/A

### Content Changes

- Updated the agent creation workflow in all labs to reflect the latest Copilot Studio UI, where agent naming is now handled through a direct pop-up window.
- Added Scenario sections across all labs and updated the Overview sections accordingly.
- Updated Lab 5, Task 1 with additional steps to create a new connection for the Weather Forecast connector.
- Replaced blurred screenshots with updated images.
- Refined wording and instructional clarity in multiple steps throughout the labs.

### Screenshot Updates

- Updated screenshots across all labs to match the latest Copilot Studio experience.
- Replaced outdated or blurred images with clearer screenshots.
      
### Testing Notes

- **Testing Date**: 2026-05-22

### Testing Scope 

Performed end-to-end validation of the lab, ensuring all steps work as expected. Updated the lab guide with clear and accurate instructions.

---
</details>

<details>
  <summary>2026-04-21</summary>

## Release Date: 2026-04-21

### Summary of Changes

Updated the lab guide to improve clarity and align with the latest Copilot Studio experience. Removed hardcoded values, introduced dynamic inputs, and added guidance to address common issues.

### Infrastructure Changes

N/A

### Content Changes

Updated instructions to improve clarity and alignment with the latest UI

**Lab 02 – Task 1:**
- Added a note clarifying that “Speech variation available” is a default feature and not related to voice.

- Included guidance to resolve environment validation issues by refreshing and selecting the correct environment.

**Lab 03 – Task 2:**
- Added a note explaining the expected behavior of User’s entire response, where conditions match only exact keywords, with an example.

- Provided instructions to manually add the DestinationCity variable to ensure correct usage.

**Lab 05 – Task 1:**

- Removed hardcoded weather input and replaced it with a dynamic variable.

- This allows users to provide input and makes the flow more flexible.

### Screenshot Updates

- **Minor updates**: Minor screenshot updates to align with flow of the lab .
      
### Testing Notes

- **Testing Date**: 2026-04-21

### Testing Scope 

Performed end-to-end validation of the lab, ensuring all steps work as expected. Updated the lab guide with clear and accurate instructions.

---
</details>

<details>
  <summary>2026-04-03</summary>

## Release Date: 2026-04-03

### Summary of Changes

Accommodated major Copilot Studio UI updates and refined instructions to improve understanding and clarity.

### Infrastructure Changes

N/A

### Content Changes

Minor instructional updates to align the steps with the current Copilot Studio UI.

### Screenshot Updates

- **Major updates**: Major screenshot updates to align with latest Copilot Studio UI updates.
      
### Testing Notes

- **Testing Date**: 2026-04-03

### Testing Scope 

 Performed end-to-end testing of the lab with all validations successfull, updated the lab guide with clear instructions.

---
</details>

<details>
  <summary>2026-02-27</summary>

## Release Date: 2026-02-27

### Summary of Changes

Accommodated major Copilot Studio UI updates and refined instructions to improve understanding and clarity.

### Infrastructure Changes

N/A

### Content Changes

Minor instructional updates to align the steps with the current Copilot Studio UI.

### Screenshot Updates

- **Major updates**: Major screenshot updates to align with Copilot Studio UI.
      
### Testing Notes

- **Testing Date**: 2026-02-27

### Testing Scope 

 Performed end-to-end testing of the lab with all validations successfull, updated the lab guide with clear instructions.

---
</details>

<details>
  <summary>2026-02-03</summary>

## Release Date: 2026-02-03

### Summary of Changes

Some minor updates were introduced to reflect the latest UI screenshots and to make the instructions easier to understand.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: The screenshots have been updated to align with the latest Copilot Studio user interface.

### Testing Notes

- **Testing Date**: 2026-02-03

### Testing Scope 

- Successful end-to-end lab testing was completed, and the lab guide was updated to reflect the latest UI changes and improve overall clarity.

---
</details>
<details>
  <summary>2026-01-02</summary>

## Release Date: 2026-01-02

### Summary of Changes

Update includes minor improvements such as enhanced UI screenshots and revised instructions for better clarity and precision.


### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Screenshots have been updated to align with the latest updates in the UI.
    
### Testing Notes

- **Testing Date**: 2026-01-02

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully.

---
</details>

<details>
  <summary>2025-12-01</summary>

## Release Date: 2025-12-01

### Summary of Changes

This update includes minor improvements such as enhanced UI screenshots and revised instructions for better clarity and precision.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Screenshots have been replaced to align with the latest updates in the user interface.
    
### Testing Notes

- **Testing Date**: 2025-12-01

### Testing Scope 

- Completed end-to-end lab testing with all validations passing successfully. The lab guide was subsequently updated to enhance clarity and usability.

---
</details>

<details>
  <summary>2025-11-17</summary>

## Release Date: 2025-11-17

The internal testing is currently in progress, and the final pointers will be updated upon its completion.

</details>

<details>
  <summary>2025-10-13</summary>

## Release Date: 2025-10-13

### Summary of Changes

Updated the lab by including the latest, clearer UI screenshots and refining the instructions to enhance clarity, accuracy, and ensure a seamless learning experience. 

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: 

    - **Updated UI Screenshots**: Replaced outdated and blurry screenshots with new ones to align with the latest user interface.

### Testing Notes

- **Testing Date**: 2025-10-13

### Testing Scope 

Conducted end-to-end validation and prerequisite verification.

---

</details>


