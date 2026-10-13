# Implement Microsoft Defender for Endpoint

Welcome to the **Implement Microsoft Defender for Endpoint** lab release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team : Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

In this section, we will track and list each change introduced in the latest release:

<details>

<summary>2026-10-09</summary>

## Release Date: 2026-10-09

### Summary of Changes

Updated the Implement Microsoft Defender for Endpoint lab guides to align with the latest Microsoft Defender, Microsoft Purview, Microsoft Entra and Microsoft Intune portal experiences, and resolved a cross-lab blocker between Lab 05 and Lab 06.

### Infrastructure Changes

N/A

### Content Changes

- **Getting Started**
  - Added the **Resize the Virtual Machine View** section.
- **Lab 01 – Implement Microsoft Defender for Endpoint**
  - Task 1: Updated the Defender portal navigation to **Investigation & response > Incidents & alerts > Alerts** (Email & collaboration alerts is no longer available).
  - Task 1: Rewrote the Purview role group assignment steps (select role group > Edit under Members > Choose users > Done > Confirm) and updated the "Repeat steps" reference.
  - Task 1: Updated the Device discovery navigation to **Setup & configuration > Settings > Device discovery** and merged the related steps.
  - Task 2: Updated the Sg-IT group creation steps for the new **Microsoft Entra roles can be assigned to the group** toggle (Yes/No confirmation removed).
  - Task 3: Updated the navigation to **Setup & configuration > Settings > Endpoints**.
- **Lab 02 – Onboard Machines**
  - Task 1: Updated the onboarding navigation to **Setup & configuration > Settings > Endpoints > Device management > Onboarding** and merged the related steps.
- **Lab 03 – End to end EDR**
  - Task 3: Updated the navigation to **Setup & configuration > Settings > Endpoints** and the **Optional features** page for Live Response.
- **Lab 05 – Configure & Test Defender for Endpoint capabilities**
  - Task 2: Updated the navigation to **Setup & configuration > Settings > Endpoints** and **Optional features**.
  - Task 2: Added a note to not select the **Web-based email** category in the WCF policy, as it blocks Outlook on the web required in Lab 06.
  - Task 3: Removed the **roundcube.net** (Web-based email) test; the policy is now validated using the **Games** category only.
  - Task 4: Updated the device group navigation to **Setup & configuration > Permissions**.

### Screenshot Updates

- **Getting Started:** vmresize1.png
- **Lab 01:** microsoftdefender.png, securityadmin.png, securityadminedit.png, selectuser.png, Doneuser.png, worning.png, devisediscovery12.png, newgroup11.png, defendermenu.png, endpointsecurity.png
- **Lab 02:** onboarding.png
- **Lab 03:** task2and3.png, lab3task3step3.png
- **Lab 05:** setupconfig.png, optionalfeachers.png, webuncheck.png, blockedcontent1.png, permitions.png

### Testing Notes

- **Testing Date**: 2026-10-09
- **Known behavior:** A new tenant needs time to provision before the lab works fully: Purview role groups and device onboarding, Device discovery, Endpoints settings and vulnerability data. The lab requires **one day prior deployment** before use.

### Testing Scope

- Performed end-to-end testing of Getting Started and Lab 01 to Lab 06, validated the updated portal navigation and steps, and resolved the Lab 05 WCF policy blocker affecting Outlook access in Lab 06.

---
</details>

<details>

<summary>2026-05-22</summary>

## Release Date: 2026-05-22

### Summary of Changes

Onboarded and updated the lab exercises to align with the latest Implement Microsoft Defender for Endpoint features and security workflows.

### Infrastructure Changes

N/A

### Content Changes

- Updated the lab exercises to include the latest Microsoft Defender for Endpoint capabilities and portal experience.
- Refreshed the lab guidance to align with the latest endpoint security and onboarding workflows.
- Improved the lab instructions for better clarity and user experience.

### Screenshot Updates

N/A

### Testing Notes

- **Testing Date**: 2026-05-22

### Testing Scope

- Performed end-to-end lab testing and validated the updated Microsoft Defender for Endpoint workflows.

---
</details>




