# Secure Agentic Software Delivery: Code, Test, Scan and Ship

Welcome to the **Secure Agentic Software Delivery: Code, Test, Scan and Ship** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-11-04</summary>

## Release Date: 2026-11-04

## Summary
Completed the lab onboarding. Prepared and reviewed the lab environment, deployment configuration, and lab content to ensure smooth provisioning and execution.

## Infrastructure
* Configured the lab infrastructure using an ARM template, a Custom Script Extension.
* Added the required tools, packages, and modules to the deployment (Visual Studio Code, GitHub Copilot, Git, JDK 17, and the WebGoat source code with its Maven dependencies), so the lab environment is ready to use when it launches.
* Configured the required access for the lab environment, including the GitHub account in the lab organization with GitHub Copilot and GitHub Advanced Security licenses.
* Automation of the GitHub prerequisites is in progress. For now, these steps have been added to the lab guide (Getting Started page) for users to complete manually:
  * Creating and applying the Advanced Security configuration (secret scanning with push protection, dependency graph, and Dependabot alerts) to the lab repository.
  * Allowing GitHub Actions and enabling Copilot Autofix at the organization level.
  * Running the first CodeQL and Dependency Graph Upload scans.
  * Verifying (or creating) the **main-protection** branch ruleset.

## Content
This is a guided hands-on lab. The lab guide includes a Getting Started page with the lab scenario, overview, objectives, architecture, and component explanations, followed by five exercises. Each exercise has a scenario, objectives, and step-by-step tasks with screenshots, so users can run a secure agentic delivery loop end to end for the Contoso Health Services WebGoat application (ticket WG-1427, Report Card CSV Export):
* **Exercise 1: Threat-Model Before You Code** – Review the feature spec and generate a lightweight STRIDE threat model with Copilot.
* **Exercise 2: Agentic Development, Human-Reviewed** – Use Copilot Agent Mode to build the feature, run tests, and review the multi-file diff.
* **Exercise 3: Scan: Secrets, Code & Supply Chain** – Secret scanning push protection, CodeQL remediation with Copilot Autofix, and dependency review.
* **Exercise 4: Ship with Security Gates in CI** – Generate a gated GitHub Actions workflow with Copilot, make the checks required, and merge.
* **Exercise 5: Measure the Outcome (Stretch)** – Record test coverage, vulnerabilities remediated, and change cycle time.

Added the required lab files to the lab environment.

## Validation
* Verified the lab deployment.
* Confirmed that the required configurations and lab files are present in the lab environment.
* Tested the lab end-to-end from a user's perspective and verified that the lab can be completed successfully.

## Testing Scope
* Tested and validated the lab end-to-end successfully.

</details>
