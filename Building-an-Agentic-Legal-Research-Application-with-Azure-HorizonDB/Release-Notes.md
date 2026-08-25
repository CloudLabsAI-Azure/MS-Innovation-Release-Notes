# Building an Agentic Legal Research Application with Azure HorizonDB

Welcome to the **Building an Agentic Legal Research Application with Azure HorizonDB** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

**This is a newly onboarded lab.**

# Release Notes

<details>
  <summary>2026-08-25</summary>

## Summary of Changes

Made content, screenshot, and troubleshooting updates across Exercises 1, 3, 4, and 5 to reflect recent UI changes and user feedback. Clarified navigation steps for Foundry resources and model deployment paths, added notes about default tab behavior, and introduced targeted troubleshooting guidance for notebook and NotFoundError issues.

## Infrastructure Changes

NA

## Content Changes

- Exercise 1
  - Task 1 (Step 6): Added a note (with screenshot) instructing users to navigate to the Foundry resource page and select the newly created resource.
  - Task 1.2: Added a note explaining that users will either land on the All Resources page (where they must select the project) or land directly in the Foundry project.
  - Added a note stating that the Agent tab is selected by default when clicking the Build tab.
  - Applied the updated deployment path guidance (see Screenshot Updates) from Step 4 to Steps 8 and 12 to keep the workflow consistent.

- Exercise 3
  - Added a dedicated troubleshooting section immediately following the Objectives section to surface common issues earlier in the flow.
  - Task 4 (Step 4): Added a troubleshooting note for NotFoundError issues advising users to check their .env file, rerun the affected cells, and restart the notebook if needed.

- Exercises 4 & 5
  - Added standard troubleshooting guidelines before working with notebook cells. Recommended steps include checking the .env file, rerunning cells, restarting the notebook, and verifying the active kernel.

## Screenshot Updates

- Updated the model deployment screenshots to reflect the new UI path:
  - Previous Build: Models > Deployments
  - Current Build: Deployments > Deployed models
- Added a new screenshot to Task 1 (Step 6) showing the Foundry resource page and the newly created resource selection.
- Ensured screenshots referenced in Steps 4, 8, and 12 are consistent with the current deployment path and the Build tab’s agent-default behavior.



## Testing Notes

- **Testing Date**: 2026-08-24
- Performed focused verification of updated screenshots, navigation notes, and troubleshooting text. Confirmed that the updated model deployment screenshots and the Foundry resource screenshot reflect the current portal flows.

## Testing Scope

- End-to-End Testing: Completed a full end-to-end test and validation of all exercises to ensure seamless execution.

- Feedback Integration: Carefully reviewed all feedback details and successfully incorporated the requested notes, troubleshooting steps, and UI updates.

- Final Quality Check: Verified that all instructions and paths accurately align with the latest platform behavior before final sign-off.

---

</details>

<details>
  <summary>2026-08-03</summary>

## Summary of Changes

Completed end-to-end testing for the **Building an Agentic Legal Research Application with Azure HorizonDB** lab. All content updates, infrastructure updates, and screenshot changes were completed successfully. The lab was thoroughly reviewed, finalized, and all changes were pushed to production.

## Infrastructure Changes

- Validated Azure HorizonDB deployment workflow and access requirements.
- Verified RBAC permissions, custom role assignments, and usage policies required for successful lab execution.
- Confirmed deployment configuration and environment readiness.

## Content Changes

- Completed content onboarding across all exercises.
- Updated instructions, notes, and navigation flow for improved learner experience.
- Reviewed and updated lab content to ensure consistency and accuracy.

## Screenshot Updates

- Updated screenshots across the lab to align with the latest implementation.
- Verified all images match the current Azure and Azure HorizonDB experience.
- Refreshed screenshots for updated workflows and instructions.

## Testing Notes

- **Testing Date**: 2026-08-03

## Testing Scope

- Completed end-to-end testing of the entire lab.
- Verified all exercises, tasks, and deployment workflows.
- Confirmed content accuracy, formatting, navigation flow, and expected outputs.
- Verified screenshot alignment with the latest user interface.
- Successfully pushed all finalized changes to production.

---

</details>
