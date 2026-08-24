# Building with Azure Container Apps Sandboxes

Welcome to the **Building with Azure Container Apps Sandboxes** Readme.md. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team.`

`Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes

<details>
  <summary>2026-08-21</summary>

## Lab objectives

- Module 0: Introduction & Environment Setup
  - Task 1: Install the Azure Container Apps CLI
  - Task 2: Sign in and verify your prerequisites

- Exercise 01: First Sandbox — Group, Boot & Exec
  - Task 1: Create a sandbox group (region, VNet, identity, quota)
  - Task 2: Boot your first sandbox from a default image
  - Task 3: Inspect sandbox state and size (vCPU / memory)
  - Task 4: Run commands with exec and attach an interactive shell

- Exercise 02: Working Inside a Sandbox
  - Task 1: Execute arbitrary code with strong isolation
  - Task 2: Upload and download files over the data plane
  - Task 3: Expose an HTTP port and open a live preview
  - Task 4: Tag sandboxes with labels and metadata

- Exercise 03: Lifecycle — Suspend, Resume & Snapshots
  - Task 1: Suspend a sandbox to persist memory + disk and scale to zero
  - Task 2: Resume in place and confirm full context is restored
  - Task 3: Capture a snapshot and fork it into multiple replicas
  - Task 4: Tear down sandboxes cleanly

- Exercise 04: Customization — Images, Volumes, Secrets & Identity
  - Task 1: Import an OCI container image and use it as the root filesystem
  - Task 2: Attach a volume (Azure Blob) for shared data
  - Task 3: Inject secrets as environment variables at boot
  - Task 4: Attach a managed identity for token-broker access to Azure

- Exercise 05: Securing Egress
  - Task 1: Understand deny-default outbound and host allowlists
  - Task 2: See credential injection at the proxy
  - Task 3: Test an allowed host vs. a blocked host

## Infrastructure Changes

- **Change**: This is a newly onboarded lab. The ARM template deploys a Windows Server 2019 CloudLabs jump VM (`Standard_D2ads_v4`) with its managed OS disk, virtual network, network interface, public IP address, and network security group. All resources are created in a single resource group named `SandBox-<DeploymentID>`.
- **Change**: API versions set to the latest stable releases — `Microsoft.Compute/virtualMachines` at `2025-11-01` and all `Microsoft.Network` resource types at `2025-07-01`. The template schema was updated to `2019-04-01` and `dependsOn` entries converted to `resourceId()` expressions.
- **Note**: The sandbox group and all sandbox resources are created by the learner during the lab rather than pre-provisioned. The `Microsoft.App/SandboxGroups` resource type is not reliably deployable through ARM during public preview.

## Content Changes

- **Change**: New lab guide authored covering Module 0 and Exercises 01 through 06, aligned to the lab Table of Contents and a 60-minute duration.
- **Change**: Module 0 updated to include installation of the `aca` CLI, interactive `az login`, subscription configuration for the CLI, and the role assignment step.
- **Change**: All resource group references consolidated to the single lab resource group `SandBox-<DeploymentID>`.
- **Change**: Inject keys moved out of fenced code blocks into prose, as CloudLabs does not substitute inject values inside code blocks.
- **Change**: Command placeholders quoted or replaced with example values so that unsubstituted placeholders do not fail with a Command Prompt redirection error.
- **Change**: Subnet delegation requirements documented in Exercise 01 for reference, along with the constraints that apply if VNet integration is ever added.
- **Change**: Supporting collateral produced — workshop presentation, support handover manual, and lab cost estimate.

## Testing Notes

- **Testing Date**: 2026-08-21

- **Issues Found**:
  - The `aca` CLI was not present on the lab virtual machine and had to be installed manually. It is a standalone signed binary, not an npm package, and does not require Node.js.
  - The `aca` CLI does not inherit the active subscription from `az`, failing with `Error: subscription ID required (use -s or ACA_SUBSCRIPTION)`.
  - `az login -u <user> -p <pass>` fails with `invalid_grant AADSTS50126`, as a Temporary Access Pass cannot be supplied on the command line.
  - `az role assignment create` fails with `AuthorizationFailed` on `Microsoft.Authorization/roleAssignments/write` for the lab account.
  - Unsubstituted `<PLACEHOLDER>` values fail in Command Prompt with `The syntax of the command is incorrect`, because `<` and `>` are redirection operators.
  - Several CLI commands in the initial draft did not match the shipped CLI: `--wait` is `--wait-timeout`, `--location` is not accepted on `sandbox create`, `snapshot` takes no `create`/`list` subcommands, and `disk` and `volume` are managed under `sandboxgroup` rather than `sandbox`.
  - `--host-allow` is not a valid flag on `egress set`; rules use `--rule "host:Action"`.
  - The egress policy YAML rejected `secretRef` and `format`, reporting that the header operation requires `value` or `valueRef`.

- **Updates**:
  - Module 0 now installs the `aca` CLI from PowerShell and configures the subscription with `aca config set -s`.
  - Sign-in changed to interactive `az login`, with `--use-device-code` documented as a fallback.
  - The role assignment step now uses inject-driven values and notes that `aca doctor` reports red until it is completed.
  - Guide commands corrected against the shipped CLI (`aca 1.0.0-preview.1`).
  - Placeholders quoted or replaced with example values throughout.

- **Resolved Issues**: All of the above have been addressed in the lab guide, with the exception of the role assignment permission, which requires the lab account to hold User Access Administrator or Owner on the resource group, or the role to be pre-assigned at deployment.

- **Known Limitations**: Azure Container Apps Sandboxes are in public preview. CLI commands, flags, and behaviour may change without notice, and sandboxes created during preview may need to be recreated after a service update. Region availability is not uniform; Sweden Central has been verified working, with East US 2 and West US 2 as alternatives.

---
</details>

