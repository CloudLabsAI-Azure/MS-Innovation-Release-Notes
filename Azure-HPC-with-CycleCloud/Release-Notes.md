# Azure HPC with CycleCloud

Welcome to the **Azure HPC with CycleCloud** Release Notes repository. In this repo, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This repository contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

<details>
  <summary>2026-07-31</summary>

## Release Date: 2026-07-29

### Summary of Changes

Updated the lab to align with the latest Microsoft CycleCloud Slurm Workspace release. The deployment process was modified to support the new Workspace Reference model and the latest deployment parameters introduced in the Microsoft repository. Minor lab guide updates were also made to improve deployment accuracy and maintain compatibility with the latest release.

### Infrastructure Changes

- Updated the deployment to use the latest **Workspace Reference** instead of a fixed commit.
- Updated the `deploy-ccws.sh` script to support the latest deployment parameters and schema changes introduced in the Microsoft repository.
- Updated the default CycleCloud Marketplace image reference to match the latest supported release.

### Content Changes

- Updated deployment instructions to reflect the latest deployment process.
- Added guidance to ensure the Workspace Reference is kept in sync with the latest Microsoft repository release to avoid deployment failures.

### Screenshot Updates

- **Minor updates**: Refreshed screenshots and instructions where required to reflect the latest deployment workflow and UI changes.

### Testing Notes

- **Testing Date**: 2026-07-29

  Performed complete end-to-end validation of the lab. Identified and resolved a deployment issue in **Exercise 1 Task 4 Step 14**, where the `deploy-ccws.sh` deployment failed due to the CloudLabs repository referencing an older commit while the Microsoft repository had introduced newer deployment changes. Updated the `.env` file to use the latest Workspace Reference and modified the deployment script to support the new deployment parameters. The lab was successfully validated after these changes.

### Testing Scope

- Performed complete end-to-end lab testing.
- Validated the deployment using the latest Microsoft CycleCloud Slurm Workspace release.
- Verified the updated deployment parameters and Workspace Reference configuration.
- Updated the deployment script and lab guide to maintain compatibility with the latest Microsoft repository changes.
- Verified successful deployment after implementing the required updates.

</details>

<details>
  <summary>2026-04-10</summary>

## Release Date: 2026-02-10

### Summary of Changes

Minor updates were implemented across the guide, including clearer and more accurate UI screenshots. Several instructions were refined to improve clarity, align with the latest interface changes, and enhance the overall user experience for learners. Step-level guidance has been improved in multiple tasks to reduce ambiguity and ensure smoother navigation during the lab.

### Infrastructure Changes

N/A

### Content Changes

N/A

### Screenshot Updates

- **Minor updates**: A few screenshots were refreshed to reflect the latest UI changes. Corresponding instruction text was reviewed and adjusted to match the updated visuals, ensuring consistency between steps and images.

### Testing Notes

- **Testing Date**: 2026-02-10
  
  Testing activities were carried out on the same date to validate the latest content, screenshots, and feature behavior.

### Testing Scope 

- Performed complete end-to-end lab testing with the new content. Verified all instructions, interactions, and user flows with the latest UI. 
- Updated the lab guide content and screenshots where necessary to ensure full compatibility with current platform behavior.

</details>
