# Advanced Workflow Automation with GitHub Actions V2 Content:

Welcome to the **Advanced Workflow Automation with GitHub Actions** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

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
  <summary>2025-10-16</summary>

## Release Date: 2025-16-11

### Summary of Changes 

-  Added explicit navigation steps in the lab guide and incorporated multiple screenshots to improve clarity and ensure correct environment access.

### Infrastructure Changes

- NA

### Content Changes

- Included detailed navigation instructions to ensure users access the appropriate development environment.

### Screenshot Update

- Updated multiple screenshots to make the instructions clearer and improve the overall experience.
  
### Testing Notes

- **Testing Date**: 2025-10-16

### Testing Scope 

- Validation covered infrastructure compatibility, lab flow continuity, content accuracy, and screenshot alignment with the latest UI.

-------------

</details>

<details>
  <summary>2025-08-20</summary>

## Release Date: 2025-08-20

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

- **Testing Date**: 2025-08-20

### Testing Scope 

 Conducted end-to-end architecture validation, cost estimation checks, and prerequisite verification.

---
</details>

<details>
   <summary>2025-05-27</summary>

### Release Date: 2025-05-27

## Infrastructure Changes

NA

## Content Changes

## Screenshot Updates

- **Change**: Updated and added screenshots at required steps

## Validation

All the validations are working fine as expected.

## Testing Notes

- **Testing Date**: 2025-05-27
- **Issues Found**: NA
- **Resolved Issues**: NA
---
</details>

<details>
   <summary>2025-05-21</summary>

### Release Date: 2025-05-21

## Infrastructure Changes

NA

## Content Changes

- **Change**:
    1. Updated lab guide with proper instructions.
    2. Tested the lab till Lab 5 as the issue in Lab 6 still exists.
    3. Validations steps are updated(organization name and PAT token needed) as the lab got updated with github SSO credentials and all of them are getting validated.

## Screenshot Updates

- **Change**: 

    1. Screenshots have been updated as per new UI changes and updated instructions.

## Testing Notes

- **Testing Date**: 2025-05-21
- **Issues Found**: NA
- **Resolved Issues**: NA

---
</details>


<details>
   <summary>2025-05-16</summary>

### Release Date: 2025-05-16

## Infrastructure Changes

1. Added Github SSO and updated the custom script 

## General Updates
- Included Multi-Factor Authentication (MFA) steps with updated screenshots in the **"Getting Started"** page.
- Updated all workflow names across relevant labs for consistency.
- Validation steps updated to require **organization name** and **Personal Access Token (PAT)** due to integration with **GitHub SSO**.
- Assigned names to all workflows, made necessary modifications to the workflow and YAML files, and updated the corresponding screenshots accordingly.

## Lab 1: Introduction to GitHub Actions
- Updated lab content with revised instructions and screenshots.
- Modified the `jobs.yml` file to align with content changes.
- 
## Lab 2: Building and Pushing Docker Images with GitHub Actions
- Created a new `docker.yml` file to configure a GitHub Actions workflow for building and pushing Docker images to **Azure Container Registry (ACR)**.
- Integrated steps to log in to ACR and push the Docker image.
- Validated successful deployment by browsing image content via **container instance Public IP**
## Lab 3: Security with GitHub Advanced Security
- Combined **Task 2 and Task 3** for better clarity and workflow.
- Removed **Dependabot scanning and alert enabling** steps.
- Updated **Task 3** steps to import the repository manually due to private organization settings (forking not allowed).
- Modified `package.json` file with necessary updates.
- Updated `nodejs_ci.yml` to include relevant `npm` packages.
- Revised `codeql-analysis.yml` and added **AI-based code scanning fix steps**.
## Lab 4 & Lab 5: OIDC and GitHub Deployment Best Practices
- Swapped the content between **Lab 4 and Lab 5**:
  - **OIDC Integration** moved to **Lab 5**
  - **Deployment Best Practices** content now in **Lab 4**
- Reordering aligned with current best practices for better learning flow.
- Updated workflow names accordingly.
## Lab 6: Final Integration and Validation
- Resolved all issues in Lab 6.
- Updated the screenshots and tested a new approach by forking the repository under a new organization and integrating it with Azure DevOps

## Content Changes

## Screenshot Updates

- **Change**: 

    1. Screenshots have been updated as per new UI changes and updated instructions.

## Testing Notes

- **Testing Date**: 2025-05-16
- **Resolved Issues**:
- Investigate the trigger issues in hello.yml. and fixed it
- The integration issue with Azure DevOps in Lab 6 has been resolved.
- 
---
</details>







