# Application Modernization 1 Day:

Welcome to the **Application Modernization 1 Day** Readme.md . In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

## Release Notes

<details>
  <summary>2025-09-30</summary>
  
## Release Date: 2025-09-18

### Summary of Changes

- Instructions and Images have been updated to accomodate the newer changes in Azure AI Search
- Additional enhancements in images and instructions in the Solution guide for easier navigation and understanding

## Testing Notes

- **Testing Date**: 2025-09-30

### Testing Scope 

- End to End testing has been performed and Validations are Succeded 

---
</details>

<details>
  <summary>2025-08-26</summary>
  
## Release Date: 2025-09-18

### Summary of Changes

- In Challenge 2, accommodated the feedback shared by the Customer to update Task 1 by removing the instructions and adding a file provided.
- Added additional details to the Attendee Guide and Trainer Guide. This included updating the instructions to incorporate recent changes in the Azure UI.

## Testing Notes

- **Testing Date**: 2025-08-26

### Testing Scope 

- Performed end-to-end lab testing and updated the lab guide for better clarity.  

---
</details>

<details>
  <summary>2025-05-23</summary>

## Infrastructure Changes

NA

## Content Changes and Screenshot Updates

### **Solution Guide Enhancements**

**Challenge 2:**

* Lab 2: Included a note instructing users to click **Accept** if a cookie consent pop-up appears.
* Lab 2: Provided instructions and screenshots for verifying the account with a phone number, which is required to enable API access.
* Lab 2: Noted that users should click **Agree** if prompted with Terms of Use.
* Lab 2: Replaced outdated screenshot of the "Set email preferences" prompt with the latest "Update email preferences" UI.
* Lab 2: Updated the screenshots reflecting the current steps to navigate and create the API key.
* Lab 2: Substituted the previous NGC key and Docker run command with the current instructions for launching the NVIDIA Riva ASR container.

**Challenge 3:**

* Task 2: Removed the instruction to run Docker as a daemon, as per instructor feedback.
* Task 3: Revised the UI prompt for Azure login to reflect the current message: *"Automatically sign in to all desktop apps and websites on this device"*, and instructed users to select *“No, this app only.”*
* Task 5: Replaced the hardcoded check-in/check-out dates with guidance to select future dates when adding a booking via the hosted app.

**Challenge 4:**

* Updated the instructions for configuring CORS policies, noting that this setting is now located under the **Networking** tab in the Azure portal, with refreshed screenshots reflecting the current UI.

**Challenge 5:**

* Clarified that the “RAG model” must be selected on the **“What scenario are you targeting?”** page during Azure AI Search configuration for extracting brochure data.

**Challenge 7:**

* Task 1:

  * Reorganized and aligned screenshots with corresponding instruction numbers.
  * Included steps and visuals for locating the PostgreSQL endpoint URL.
  * Added a step to exit the chat terminal after interaction.
* Task 2:

  * Directed users to reference the correct container registry from a previous challenge.
  * Updated login instructions to reflect the current Azure CLI prompt.
  * Noted the possibility of the bot responding with a follow-up question.

---

###  **Scenario Guide Enhancements**

**Challenge 2:**

* Lab 2: Updated the UI screenshot of the "Set email preferences" dialog to match the current "Update email preferences" layout.
* Lab 2: Updated the navigation steps and screenshot for API key creation to reflect UI changes.
* Lab 2: Updated the Docker run command and NGC key for launching the NVIDIA Riva ASR container.

**Challenge 3:**

* Task 4: Introduced a CLI command to guide users in deploying the PostgreSQL server instance, as recommended by a participant.

**Challenge 4:**

* Refactored the guidance to clearly separate frontend and backend components by copying respective files into designated folders using specific CLI commands.
* Introduced CLI steps to build and push frontend/backend containers to Azure, including the use of `az containerapp env create`.
* Transitioned CORS policy configuration steps from CLI-based to portal-based to improve usability.

**Challenge 5:**

1. Expanded role assignment instructions to include all necessary permissions:

   * Storage Blob Data Contributor
   * Cognitive Services OpenAI Contributor
   * Search Index Data Contributor
   * Search Index Data Reader
   * Search Service Contributor
2. Clarified the file upload path by specifying that brochures are located in `Assets\PDFs`.
3. Specified the use of **"brochures-vector"** as the index name for Azure AI Search.

**Challenge 6:**

1. Clarified that the *Storage Blob Data Owner* role must be assigned to the Azure user for the storage account.
2. Noted that participants must select the **Chat** flow type when uploading `chatflow-oai-datasources.zip` into Prompt Flow.
3. Included PostgreSQL setup commands to create the `promptflow` user and assign necessary permissions for accessing tables and functions.

**Challenge 7:**

* Included a PowerShell script for setting environment variables and establishing required connections using the `pf connection create` command.
* Instructed users to copy `azure_openai.yaml`, `azure_ai_search.yaml`, and `postgresql.yaml` into the `.\docker-dist\connections` directory.
* Provided full `az containerapp create` command to deploy the chatbot container app with necessary environment variables and secrets.
* Included `az containerapp update` commands to configure the `CHATBOT_BASEURL` for both frontend and backend services.




## Testing Notes

- **Testing Date**: 2025-05-23
- **Resolved Issues**: Since there was UI Updates in AI foundry portal in Challenge 6, resolved the issue by deploying the neccessary resources through Azure portal.

---
</details>

