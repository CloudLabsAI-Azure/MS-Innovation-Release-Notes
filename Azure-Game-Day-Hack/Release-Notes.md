# Azure Game Day Hack

Welcome to the **Azure Game Day Hack** Readme.md. In this, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots,[...]

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

<details>
  <summary>2026-11-17</summary>

## Release Date: 2026-11-17

### Summary of Changes

Updated the AI-Powered Cloud Operations on Azure – Azure GameDay Hack lab based on end-to-end testing and customer/tester feedback. The Challenge Guide and Solution Guide were updated to match current portal UI (Microsoft Defender portal, VM Insights Configure monitor page, AI Search Import data wizard), and incorrect steps were fixed (Challenge 02 workbook metric, Challenge 03 entity mapping). The manual Defender for Endpoint onboarding and incident generation steps are now automated with a logon task, AI Search permissions are configured by the template, and quiz questions that rejected correct answers were fixed.

### Infrastructure Changes

- Automated the Defender for Endpoint onboarding and incident generation for Challenge 03, replacing the manual post-deployment steps. The deployment status stays Pending until this completes.
- Configured Azure AI Search with a managed identity and the required data access roles for the search service and the lab user, so the Import data wizard and Search explorer work without permission errors.
- The hotel sample data is now uploaded to a dedicated `hotels-sample` blob container for Challenge 06.

### Content Changes

- **00_Overview.md**
  - Challenge 03 description updated to reference the Microsoft Defender portal's Attack graph. Fixed a duplicated-word typo.
- **Challenge 01 (Challenge Guide)**
  - Added a Sign in to the Azure portal section with the username and Temporary Access Pass.
  - Task 1: simplified navigation to Application Insights and added the Server response time check.
  - Task 2: added a hint for the chart's time range and granularity settings.
  - Task 4: restructured the SQL dependency alert into scope, condition with labelled alert logic, and action group/name/severity steps.
- **Challenge 02**
  - Challenge Guide Task 1: added a note that Application Map telemetry can take 15–30 minutes, and a hint for finding the web app URL.
  - Task 3: workbook metric corrected from *Export Failed* to **Failed requests** (Standard metrics, Count, Bar chart) in both guides. Solution Guide step rewritten to match the current workbook UI.
  - Challenge Guide Task 3: Share (link) and Pin (new shared dashboard) split into two clear actions.
- **Challenge 03**
  - Challenge Guide Task 1: updated for Sentinel incidents moving to the Microsoft Defender portal, the incidents queue filters, and the Attack graph (replaces Attack story).
  - Challenge Guide Task 2: Activity log step now mentions filtering on Administrative events and the role assignment operation. Added a step to query the pre-seeded role assignment data in Log Analytics before drilling into an event.
  - Task 3: entity mapping corrected to Account entity → `Caller` column. Added a dedicated Entity mapping step to the Solution Guide.
- **Challenge 04**
  - Challenge Guide Task 2: `CostAnomaly-LabAlert` is now entered as the alert Subject, matching the Solution Guide.
- **Challenge 05**
  - Task 1: Configure monitor step updated in both guides for the new UI (OpenTelemetry and Classic log-based metrics, recommended alerts, user-assigned managed identity).
  - Challenge Guide Task 2: replaced the outdated Top N chart step with a CPU utilization trend review.
- **Challenge 06**
    - Task 1: the Import data wizard step now specifies the **`hotels-sample`** container.
    - Instructions now reference Microsoft Foundry instead of Azure OpenAI.
- **Questions**
  - Question 08: replaced Azure OpenAI with Microsoft Foundry in the options. Answer unchanged.
  - Question 09: answer is now case-insensitive and accepts spacing variations.
  - Question 10: reworded to ask for the name or subject of the cost anomaly alert, and accepts both the Challenge Guide and Solution Guide values.
  - Question 11: answer is now case-insensitive and accepts variations such as "Enable recommended alerts".

### Screenshot Updates

- **Challenge 02:** replaced the workbook metric screenshot to show the Failed requests metric settings.
- **Challenge 03:** added a new screenshot for the entity mapping step.
- **Challenge 05:** replaced the Enable monitoring screenshot with the new Configure monitor page.
- **Challenge 06:** replaced the Import data and Search explorer screenshots to show the `hotels-sample` container and hotel search results.

### Testing Notes

- **Testing Date:** 2026-11-16

### Testing Scope

- Completed end-to-end testing of all six challenges in the lab environment.
- Identified issues found during testing and from customer feedback, and updated the Challenge Guide and Solution Guide to fix them.
- Validated the automated Defender onboarding and incident generation across multiple test deployments.
- Verified the updated quiz questions accept the correct answers.

---
</details>

