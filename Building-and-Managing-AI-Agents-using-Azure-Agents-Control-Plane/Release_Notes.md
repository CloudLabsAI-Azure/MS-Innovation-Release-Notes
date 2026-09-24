# Building and Managing AI Agents using Azure Agents Control Plane

Welcome to the **Building and Managing AI Agents using Azure Agents Control Plane** Release Notes repository. In this repo, we document the changes made during the latest testing cycle, including updates related to infrastructure, lab content, screenshots, onboarding flow, and overall learner experience improvements.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

* Testing dates
* Infrastructure and UI-related updates
* Content and instruction improvements
* Screenshot and media updates
* Validation and learner experience enhancements

For any further details or inquiries, feel free to reach out to the CloudLabs support team.
Email Support: [cloudlabs-support@spektrasystems.com](mailto:cloudlabs-support@spektrasystems.com)

# Release Notes

<details>
  <summary>2026-09-23</summary>

## Release Date: 2026-09-23

### Summary of Changes

* Updated the lab guide to improve the experience by clearly identifying lab tasks that are Read-Only and only require participants to review the provided configurations or information.
* Added Agent365 integration to the lab infrastructure.

### Infrastructure Changes

* Added Agent365 integration to the lab infrastructure.
* Updated the `disableLocalAuth` parameter to false in the **infra/main.json** file to enable creation of the Chat Completion model during **Exercise 3 > Step 3.3**.
* Removed **East US 2** and **South Central US** from the lab environment deployment regions due to:
  * Azure AI Search (Foundry IQ) capacity constraints.
  * The Standard SKU for the text-embedding-3-large model not being supported in the South Central US region.
* Updated the lab file path references in Exercise 1 from `C:\LabFiles` to `C:\LabFiles\azure-agents-control-plane`.
* Fixed Foundry authentication from the AKS pod. Updated **next_best_action_agent.py** to use **get_bearer_token_provider** for all Azure OpenAI calls instead of passing the AAD token as an API key. This ensures the Exercise 1 validation test works out of the box.

### Content Changes

* Updated lab headings to clearly indicate Read-Only steps that only require participants to review the content.
* Added relevant notes and warnings to lab steps where necessary to provide additional guidance and clarify expected behavior.

### Screenshot Updates

NA

### Testing Notes

* **Testing Date**: 2026-09-23

### Testing Scope

* End-to-end lab deployment, including logon task execution, post-provisioning, and ontology upload.
* Validation of fresh lab environment deployments and redeployment into existing environments.
* Validation of recovery from transient Azure service failures and resource name collisions.
* Verification of deployment log readability and error reporting.
---

</details>

<details>
  <summary>2026-09-21</summary>

## Release Date: 2026-09-21

### Summary of Changes

* Reworked the lab logon task to call the repository's own deployment scripts instead of a duplicated copy, removing ~390 lines of drift-prone logic and the Azure Developer CLI dependency.
* Fixed nine defects that prevented the lab deployment from completing end to end, most of which were failing silently.
* Added failure handling and diagnostics so that deployment problems are reported clearly instead of stalling or reporting false success.

### Infrastructure Changes

* Data-plane firewalls (AI Search, Storage, Container Registry, Foundry, Cosmos DB) now allow the lab VM, enabling AI Search ingestion and ontology upload to succeed.
* Deployment now targets the pre-existing `apim-mcp-aks` resource group explicitly, with a guard for resource group region mismatches.
* Corrected AKS, Storage and AI Search operations that previously failed when running under a service principal.
* Container image build and push now validate their results, preventing deployment of a non-existent image.
* Deployment lookups now select the correct, most recent successful deployment rather than an arbitrary one.
* Added a provisioning watchdog with progress reporting, so an unresponsive Azure CLI client no longer stalls the lab indefinitely.
* Deterministic failures (resource name collisions) now stop immediately with guidance, instead of retrying without effect.

### Content Changes

NA

### Screenshot Updates

NA

### Validation and Testing

#### Validation Performed

* Completed multiple end-to-end deployments across several lab subscriptions and tenants, including freshly provisioned environments.
* Verified Kubernetes rollout, LoadBalancer assignment, AI Search ingestion, and ontology upload.
* Confirmed generated test configuration files contain correct deployment values.
* Confirmed storage firewall settings are restored after the ontology upload.
* Validated syntax of all modified scripts.

### Testing Notes

* **Testing Date**: 2026-09-21

### Testing Scope

* End-to-end lab deployment from logon task through post-provision and ontology upload.
* Fresh lab environments and redeployment into existing environments.
* Recovery from transient Azure failures and resource name collisions.
* Deployment log readability and error reporting.

---

</details>


<details>
  <summary>2026-05-27</summary>

## Release Date: 2026-05-28

### Summary of Changes

* Updated onboarding guidance and learner instructions to align with the latest Azure portal workflow and lab navigation experience.
* Refreshed screenshots across exercises and onboarding pages for improved clarity and consistency.
* Improved step-by-step lab guidance and documentation flow to provide a smoother hands-on experience for learners.

### Infrastructure Changes

* Updated Azure Portal onboarding and navigation flow to match the latest UI experience.
* Adjusted learner flow and validation guidance based on recent Azure service behavior updates.

### Content Changes

* **Major updates**:

  * Revised learner instructions across multiple exercises.
  * Improved onboarding documentation and lab flow consistency.
  * Enhanced instructional clarity and formatting throughout lab manuals.
  * Fixed outdated references and aligned content with the current learner journey.

### Screenshot Updates

* **Major updates**:

  * Updated onboarding and Azure portal screenshots to align with the latest UI and workflow.
  * Refreshed exercise screenshots for improved learner navigation and understanding.
  * Replaced outdated visuals across onboarding and environment setup pages.


### Validation and Testing
NA

#### Validation Performed

* Followed the lab end-to-end after implementing updates.
* Verified instruction sequencing and learner flow continuity.
* Confirmed screenshots match the current Azure Portal UI.
* Tested all links and markdown rendering.
* Validated image references and media paths.

### Testing Notes

* **Testing Date**: 2026-05-27

### Testing Scope

* Conducted end-to-end validation of the lab environment and exercise flow.
* Verified onboarding guidance, screenshot placement, and markdown rendering.
* Reviewed instruction consistency across all exercise documents.
* Confirmed updated media assets render correctly and support the learner experience.

---

</details>
