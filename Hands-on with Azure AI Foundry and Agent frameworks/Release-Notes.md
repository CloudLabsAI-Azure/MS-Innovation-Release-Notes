# Hands-on with Azure AI Foundry and Agent frameworks

Welcome to the **Hands-on with Azure AI Foundry and Agent frameworks** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2025-06-18</summary>

### Release Date: 2025-06-18

- **Change**: Downgraded Python packages due to compatibility issues with the latest versions.
- **Testing Date**: 2025-06-18

## Infrastructure Changes

- **azure-ai-projects Package**

   - **Issue:** Exercises 2 to 6 experienced connectivity problems with Azure AI Foundry.
   - **Cause:** The latest version of the `azure-ai-projects` package was not compatible with the current setup.
   - **Solution:** Downgraded the package to version **1.0.0b10** to restore functionality.

- **semantic-kernel[azure] Package**

   - **Issue:** Exercise 6 encountered errors related to this package.
   - **Cause:** The latest version of `semantic-kernel[azure]` was incompatible with the implementation.
   - **Solution:** Downgraded the package to version **1.28.0**, resolving the issue.

- Updated the Python code in the Jupyter Notebooks to resolve the issues that were occurring   

## Content Changes

- Updated lab guide steps with the latest UI present in the Azure portal.
- Getting started page has been updated as per the new UI changes in the CloudLabs. 
  
## Screenshot Updates

- Screenshots have been updated as per the new UI changes and updated instructions.
- Updated lab guide with more screenshots wherever required.
- Getting started page has been updated as per the new UI changes in the CloudLabs.

## Testing Notes

- **Testing Date**: 2025-06-18
- **Tested Features**: Inline validations, latest UI changes, functionality of the lab.
- **Issues Found**: The Latest Python Packages were incompatible with the Jupyter notebooks used in this lab. 
- **Resolved Issues**: Downgraded Python packages that were causing issues for the Jupyter notebooks used in this lab.
---
</details>
