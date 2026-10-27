# John Tyler

Identity & Access Management · Entra ID · Azure · Cloud Security

[Portfolio](https://johncalvintyler.com) · [All repositories](https://github.com/johninfra?tab=repositories) · [Try CyberOps Triage Lab](https://johninfra.github.io/cyberops-triage-lab/)

I'm an IAM, cloud, cybersecurity, and IT infrastructure professional building hands-on expertise across Microsoft Entra ID, Azure, Microsoft 365, Windows, and security operations. My work spans identity administration, access governance, cloud administration, automation, systems troubleshooting, and security analysis, backed by practical labs and live technical projects.

I design and build governance applications, implement Conditional Access, PIM/JIT, Azure RBAC, MFA, and identity lifecycle controls, automate administrative workflows with PowerShell, Azure CLI, Microsoft Graph, and GitHub Actions, analyze Microsoft Entra sign-in telemetry with Kusto Query Language (KQL) in Azure Log Analytics, and document the configuration, troubleshooting, validation, and audit evidence behind each project.

Credentials: CompTIA Security+ · CompTIA A+ · A.S. in Computer Information Systems

## Core Skills

- **Identity administration:** Entra ID, Active Directory, users and security groups, provisioning/deprovisioning, MFA, app registrations, and Enterprise Applications.
- **Access governance:** Conditional Access, PIM, eligible vs. active assignments, JIT activation, Azure RBAC, effective-access analysis, and least privilege.
- **Azure administration and automation:** Azure resource groups, virtual networks, NSGs, Azure RBAC, Azure Policy, resource locks, monitoring, Azure CLI, PowerShell, Microsoft Graph, Azure Resource Manager, GitHub Actions, OIDC workload identity federation, and Azure Static Web Apps.
- **Log analysis and monitoring:** Kusto Query Language (KQL), Azure Monitor, and Log Analytics; Entra `SigninLogs` ingestion validation, time-based and account-specific filtering, successful/failed sign-in analysis, and result summarization.
- **Systems and security:** Windows Server, Microsoft 365, Linux, DNS/VPN troubleshooting, Splunk/SPL, Sysmon, Windows Event Logs, and endpoint diagnostics.

## Featured IAM Projects

| Project | What it demonstrates |
| --- | --- |
| [Entra PIM Group JIT Access Lifecycle Lab](https://github.com/johninfra/entra-pim-group-jit-access-lifecycle-lab) | Role-assignable Entra group, eligible administrator membership, two-hour MFA-protected PIM activation, and audited membership activation/removal using a test identity. |
| [Microsoft Entra Sign-In Monitoring with KQL](https://github.com/johninfra/entra-privileged-signin-monitoring-alerts) | Entra diagnostic settings, verified `SigninLogs` ingestion into Azure Log Analytics, and KQL queries for ingestion health and sign-ins involving monitored privileged accounts. |
| [Azure Enterprise Administration Lab](https://github.com/johninfra/azure-enterprise-administration-lab) | Azure virtual networking, NSGs, resource-scoped RBAC, Azure Policy, resource locks, activity monitoring, and Windows Server administration. |
| [Phishing-Resistant MFA with YubiKey](https://github.com/johninfra/entra-phishing-resistant-mfa-yubikey-lab) | Microsoft Entra Conditional Access, FIDO2 security key authentication with YubiKey, phishing-resistant MFA enforcement, and sign-in validation. |
| [Conditional Access + PIM/JIT](https://github.com/johninfra/entra-conditional-access-pim-jit) | Azure management MFA, emergency-access exclusions, and two-hour Contributor activation with justification and ticket metadata; validated through sign-in and Activity Logs. |
| [Azure CLI Resource Group Lifecycle Lab](https://github.com/johninfra/azure-cli-resource-group-lifecycle-lab) | Azure CLI and Cloud Shell resource-group creation, verification, deletion, and cleanup validation. |
| [MFA & RBAC Access Lifecycle](https://github.com/johninfra/azure-mfa-rbac-lifecycle-administration) | User/group administration, Authenticator enrollment, resource-scoped Reader access, and verified access revocation using a test-user session. |
| [Azure Tenant Governance Dashboard](https://github.com/johninfra/azure-tenant-governance-dashboard) | Read-only Entra/Azure inventory, MFA registration posture, privileged-role and RBAC review, governance findings, and JSON/CSV exports. |

## CyberOps Triage Lab

An interactive SOC and IAM training simulator built with React, TypeScript, and Vite. Its 27 scenarios cover alert triage, identity incidents, Azure/Entra access decisions, investigations, and ticket prioritization. Includes searchable evidence, access-path exploration, response sequencing, scoring, and detailed debriefs.

All scenarios use fictional data; no cloud tenant or account is required.

[Launch the lab](https://johninfra.github.io/cyberops-triage-lab/) · [View the source](https://github.com/johninfra/cyberops-triage-lab)

## Azure, Systems & Security Labs

- [Azure Enterprise Administration](https://github.com/johninfra/azure-enterprise-administration-lab) — Network segmentation, NSGs, RBAC, Azure Policy remediation, resource locks, monitoring, and Windows Server. [Video walkthrough](https://www.youtube.com/watch?v=ETXv-iHt-tE).
- [Azure Windows Diagnostic Automation](https://github.com/johninfra/azure-windows-diagnostic-automation-workflow) — GitHub Actions OIDC, scoped RBAC, VM Run Command, PowerShell reporting, and VM deallocation. [Diagnostic toolkit source](https://github.com/johninfra/windows-it-diagnostic-toolkit).
- [IT Support & Cybersecurity Lab Portfolio](https://github.com/johninfra/it-support-and-cybersecurity-labs) — 27 documented labs covering Active Directory, Windows/Linux administration, networking, Splunk, PowerShell, and cloud identity.
- [Azure CLI Resource Group Lifecycle](https://github.com/johninfra/azure-cli-resource-group-lifecycle-lab) — Create, verify, delete, and confirm cleanup of Azure resource groups through Cloud Shell.

## Security+ Command Center

A free, browser-based **CompTIA Security+ SY0-701 study app** I built with **300 original practice questions**, **50 interactive flashcards**, timed randomized mock exams (10, 25, 50, or 90 questions), difficulty and domain filters, answer explanations, and missed-question tracking. Includes an acronym trainer, common ports/protocols reference, and local-only study progress storage. Independent educational project; not affiliated with CompTIA.

[Launch the Security+ Command Center](https://johninfra.github.io/security-plus-command-center/) · [View the source code](https://github.com/johninfra/security-plus-command-center)
