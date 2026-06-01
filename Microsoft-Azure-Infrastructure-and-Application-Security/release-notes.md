# Microsoft Azure Infrastructure and Application Security

Welcome to the **Microsoft Azure Infrastructure and Application Security** release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, bug fixes and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

 `Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2026-05-21</summary>

## Release Date: 2026-05-21

### Summary of Changes

Performed end-to-end validation of the lab and implemented documentation-only fixes across all lab guides — typo and grammar corrections, deprecated link updates, step-order corrections, and added clarification notes to improve readability and accuracy.

### Infrastructure Changes

N/A

### Content Changes

- **01-secure-administration-and-management.md:** Fixed typos ("healthly" → "healthy", "resorces" → "resources"); reworded the refresh note; added helper notes guiding users to the next page if the `FirewallVM-nsg` resource isn't immediately visible (NSG flow logs and Diagnostic settings sections).
- **02-secure-application.md:** Updated deprecated `docs.microsoft.com` links to `learn.microsoft.com` for Azure Firewall, Application Gateway, and WAF references; corrected step order in the Front Door rate-limit rule (Priority now precedes Rule type to match the portal flow).
- **03-secure-infrastructure-with-azure-firewall-premium.md:** Fixed typo in rule collection name ("rulecolection" → "rulecollection"); improved grammar in the TLS Inspection retry instruction.
- **04-protecting-infrastructure-with-azure-ddos-protection-plans.md:** Merged redundant "Overview" / "What is DDoS protection?" headings; standardized punctuation on instruction lines; clarified the Blue tick step under Metrics.
- **05-network-management-and-monitoring-revisited-flow-logs-and-traffic-analytics.md:** Reworded the "Time interval greyed out" note for clarity; clarified the close-icon instruction in the Geo Map view.

### Screenshot Updates

- Updated `images/rlr1.png` to reflect the latest portal UI.

### Testing Notes

- **Testing Date**: 2026-05-21

### Testing Scope

- Performed end-to-end testing of the lab successfully with full validation. All lab steps were executed without any issues, and all validations passed with no errors. Everything is working as expected.
  - **Note:** A quota-related issue may occur in the East US 2 region or others. I faced the issue below during testing, and redeploying the lab to West Europe resolved it.
    - **Error Faced:** Subscription quota limitation for Basic VM SKUs prevented the deployment.

---
</details>
