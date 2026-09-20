# John Tyler

## Systems Administration · Cloud Infrastructure · Identity & Access Management · Cybersecurity

I'm an IT professional focused on **systems administration, Microsoft Azure, identity and access management (IAM), cloud security, and cybersecurity operations**.

My hands-on work includes administering **Windows, Microsoft 365, Active Directory, Microsoft Entra ID, and Microsoft Azure environments**; managing users and security groups; supporting MFA and authentication; applying group-based Azure RBAC; validating effective permissions; and testing access provisioning and revocation.

This GitHub documents practical projects across **Azure administration, Entra ID identity governance, PowerShell automation, security monitoring, vulnerability management, DevOps/CI/CD, Windows administration, networking, and IAM**. I also build browser-based security and IT operations tools that turn technical concepts into usable workflows and applications.

Recent projects include building a **live Azure Tenant Governance Dashboard** that authenticates to Microsoft Entra ID and queries Microsoft Graph and Azure Resource Manager for real tenant governance data, implementing an **Entra ID MFA and Azure RBAC access lifecycle**, building an enterprise Azure administration environment, deploying applications through **Azure Static Web Apps and GitHub Actions**, and automating Windows diagnostics with **GitHub OIDC workload identity federation, Azure RBAC, Azure VM Run Command, and PowerShell**.

**Certifications:** CompTIA Security+ · CompTIA A+

[Lab portfolio](https://github.com/johninfra/it-support-and-cybersecurity-labs) · [All repositories](https://github.com/johninfra?tab=repositories)

## Featured Projects

### [Azure Tenant Governance Dashboard](https://github.com/johninfra/azure-tenant-governance-dashboard)

Live, read-only Azure and Microsoft Entra ID governance web application built with JavaScript/Vite and MSAL. It authenticates to my Azure tenant using OAuth 2.0 Authorization Code + PKCE, queries Microsoft Graph and Azure Resource Manager for users, groups, service principals, privileged Entra roles, Azure RBAC assignments, resource groups, and available MFA registration telemetry, then generates least-privilege findings and exportable governance reports. The application is deployed from GitHub to Azure Static Web Apps through GitHub Actions CI/CD.

[Launch the live Azure app](https://icy-forest-0df58d91e.6.azurestaticapps.net) · [View the repository](https://github.com/johninfra/azure-tenant-governance-dashboard)

### [Azure MFA & RBAC Lifecycle Administration](https://github.com/johninfra/azure-mfa-rbac-lifecycle-administration)

Hands-on Microsoft Entra ID and Azure IAM lab covering user and security-group administration, Microsoft Authenticator registration, group-based Azure RBAC, least-privilege resource scoping, end-user access validation, and access revocation. Demonstrates the full access lifecycle from authentication and authorization through deprovisioning and verification.

[View the repository](https://github.com/johninfra/azure-mfa-rbac-lifecycle-administration)

### [Azure Identity Governance Console](https://github.com/johninfra/azure-identity-governance-console)

Browser-based enterprise IAM governance simulation covering identity lifecycle, security groups, Azure RBAC, access requests and approvals, privileged-access workflows, access reviews, MFA and identity-risk tracking, Conditional Access, audit logging, and portable JSON state. The application is source-controlled in GitHub, deployed through Azure Static Web Apps with GitHub Actions CI/CD, and protected with Microsoft Entra ID single-tenant OIDC authentication and Enterprise Application access controls.

[View the repository](https://github.com/johninfra/azure-identity-governance-console)

### [Azure Enterprise Administration Lab](https://github.com/johninfra/azure-enterprise-administration-lab)

Enterprise-style Microsoft Azure administration environment integrating segmented virtual networking, subnet-level NSGs, RBAC, Azure Policy and remediation, resource locks, cost governance, Azure Monitor Activity Log alerts, and Windows Server 2022 administration. Includes PowerShell validation and a full video walkthrough of the deployed environment.

[View the repository](https://github.com/johninfra/azure-enterprise-administration-lab) · [Watch the video walkthrough](https://www.youtube.com/watch?v=ETXv-iHt-tE)

### [Azure Windows Diagnostic Automation Workflow](https://github.com/johninfra/azure-windows-diagnostic-automation-workflow)

End-to-end Azure automation workflow using GitHub Actions, Microsoft Entra ID workload identity federation, OIDC, Azure RBAC, Azure CLI, VM Run Command, and PowerShell. The workflow securely authenticates without a long-lived client secret, starts an Azure Windows Server VM, executes a diagnostic toolkit remotely, generates a persistent HTML system-health report, and automatically deallocates the VM for cost control.

[View the standalone project](https://github.com/johninfra/azure-windows-diagnostic-automation-workflow) · [View Lab 27](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-27-Azure-Windows-Diagnostic-Automation-with-GitHub-Actions-OIDC)

### [Azure Static Web Apps CI/CD Lab](https://github.com/johninfra/azure-static-web-apps-cicd-lab)

Deployed two cybersecurity web applications I created—Security+ Command Center and PhishLens—from GitHub into Microsoft Azure using Azure Static Web Apps and GitHub Actions CI/CD. Documents the repository-to-cloud deployment architecture, deployment-token authorization, build configuration, automated deployment workflow, verification process, and security considerations.

[View the repository](https://github.com/johninfra/azure-static-web-apps-cicd-lab) · [Watch the Azure deployment walkthrough](https://youtu.be/Gj0A1xJ5hoo)

### [Private Wealth Cybersecurity Command Center](https://johninfra.github.io/private-wealth-cybersecurity-command-center/)

A privacy-first, browser-based cybersecurity preparedness workspace designed for high-net-worth individuals, families, family offices, and trusted advisers. It combines a guided assessment, prioritized action plan, household access mapping, incident playbooks, travel readiness, and encrypted local backup—without accounts, analytics, or a backend.

[Launch the live application](https://johninfra.github.io/private-wealth-cybersecurity-command-center/) · [View the source repository](https://github.com/johninfra/private-wealth-cybersecurity-command-center)

## Key Repositories

| Repository | What you'll find |
| --- | --- |
| [Azure Tenant Governance Dashboard](https://github.com/johninfra/azure-tenant-governance-dashboard) ([live Azure app](https://icy-forest-0df58d91e.6.azurestaticapps.net)) | Live read-only Entra ID and Azure governance dashboard using MSAL, OAuth 2.0/PKCE, Microsoft Graph, Azure Resource Manager, MFA posture review, privileged-role inventory, Azure RBAC analysis, least-privilege findings, JSON/CSV export, and GitHub Actions deployment to Azure Static Web Apps. |
| [Azure MFA & RBAC Lifecycle Administration](https://github.com/johninfra/azure-mfa-rbac-lifecycle-administration) | Hands-on IAM lifecycle lab covering Entra ID users and groups, Microsoft Authenticator registration, group-based Azure RBAC, least-privilege resource scoping, effective-access validation, and verified access revocation. |
| [Azure Identity Governance Console](https://github.com/johninfra/azure-identity-governance-console) | Enterprise IAM governance simulation covering identity lifecycle, groups, Azure RBAC, access requests, privileged access, access reviews, identity risk, Conditional Access, audit logging, Entra ID OIDC authentication, Enterprise Application access controls, and GitHub Actions CI/CD deployment to Azure Static Web Apps. |
| [Azure Enterprise Administration Lab](https://github.com/johninfra/azure-enterprise-administration-lab) ([video walkthrough](https://www.youtube.com/watch?v=ETXv-iHt-tE)) | Enterprise-style Azure environment covering VNet/subnet segmentation, NSGs, RBAC, Azure Policy remediation, resource locks, cost governance, Activity Log monitoring, Windows Server 2022, RDP, and PowerShell validation. |
| [Azure Windows Diagnostic Automation Workflow](https://github.com/johninfra/azure-windows-diagnostic-automation-workflow) | GitHub Actions automation using Entra OIDC workload identity federation, scoped Azure RBAC, Azure CLI, VM Run Command, PowerShell diagnostics, persistent HTML reporting, and automatic VM lifecycle management. |
| [Azure Static Web Apps CI/CD Lab](https://github.com/johninfra/azure-static-web-apps-cicd-lab) ([video walkthrough](https://youtu.be/Gj0A1xJ5hoo)) | Deployed two self-created cybersecurity web applications from GitHub to Azure Static Web Apps using GitHub Actions CI/CD, deployment-token authorization, custom static build configuration, and documented deployment verification. |
| [Private Wealth Cybersecurity Command Center](https://github.com/johninfra/private-wealth-cybersecurity-command-center) ([live app](https://johninfra.github.io/private-wealth-cybersecurity-command-center/)) | Privacy-first preparedness workspace for high-net-worth households and trusted advisers, featuring guided assessments, prioritized actions, access mapping, incident playbooks, travel readiness, and encrypted local backup. |
| [IT Support & Cybersecurity Labs](https://github.com/johninfra/it-support-and-cybersecurity-labs) | 27 documented labs covering Active Directory, Entra ID, Azure automation, Windows Server, Linux, Splunk, networking, PowerShell, and cloud identity, with implementation steps and screenshots. |
| [Windows IT Diagnostic Toolkit](https://github.com/johninfra/windows-it-diagnostic-toolkit) | PowerShell scripts for system health, network connectivity, Defender, firewall, service, and event log checks, plus automated HTML reporting. |
| [PhishLens — Phishing Email Detector](https://github.com/johninfra/phishing-email-detector) | Local browser analysis of pasted emails and .eml files, with explainable heuristic scoring, suspicious URL checks, sender-domain comparisons, attachment-name flags, and JSON report export. Includes a copy-and-run PowerShell launcher; no email uploads or API keys required. |
| [Security+ Command Center](https://github.com/johninfra/security-plus-command-center) | Browser-based SY0-701 study dashboard with original scenario questions, flashcards, acronyms, ports and protocols, domain-readiness tracking, missed-question review, local progress storage, and an optional PowerShell launcher. |
| [LabDesk ITSM Platform Homelab](https://github.com/johninfra/labdesk-itsm-homelab) | A simulated service desk environment connecting users, departments, assets, and tickets, with Active Directory support scenarios and troubleshooting documentation. |
| [IT AI Operations Playbook](https://github.com/johninfra/it-ai-operations-playbook) | IT standard operating procedures, AI-assisted support workflows, and automation playbooks for provisioning, ticket triage, investigations, and documentation. |
| [GitHub Profile](https://github.com/johninfra/johninfra) | The README and navigation for this portfolio. |

## Selected Labs

- **[Azure Windows Diagnostic Automation with GitHub Actions, OIDC & Azure RBAC](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-27-Azure-Windows-Diagnostic-Automation-with-GitHub-Actions-OIDC)** — Built an end-to-end cloud automation workflow that uses GitHub OIDC federation and Entra workload identity to obtain short-lived Azure access, applies resource-group-scoped RBAC, starts an Azure Windows Server VM, executes PowerShell diagnostics through Azure VM Run Command, generates a persistent HTML report, and deallocates the VM automatically.
- **[Entra ID Administration with PowerShell & Microsoft Graph](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-26-Microsoft-EntraID-Administration-with-PowerShell-and-Microsoft-Graph)** — Used Microsoft Graph PowerShell with delegated OAuth scopes to authenticate to Entra ID, enumerate users and groups, inspect privileged directory roles, validate RBAC context, and securely terminate the administrative session. [Watch the 4:37 lab walkthrough](https://youtu.be/ygk_6OC40ZE).
- **[PowerShell Vulnerability Management & Security Audit Framework](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-22-PowerShell-Vulnerability-Management-and-Security-Audit-Framework)** — Built an automated Windows endpoint assessment framework covering system and software inventory, listening ports, services, local administrators, Defender, firewall, Secure Boot, risk scoring, and HTML/JSON reporting.
- **[Splunk SIEM Security Monitoring & Alerting Platform](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-18-Splunk-SIEM-Security-Monitoring-and-Alerting-Platform)** — Deployed Splunk, ingested security telemetry, created SPL searches and dashboards, and configured real-time alerts to detect simulated reconnaissance activity.
- **[Network Traffic Analysis with Nmap, Wireshark & Splunk](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-12-Network-Traffic-Analysis-and-Security-Monitoring-with-Nmap-Wireshark-and-Splunk)** — Combined host discovery, service enumeration, packet capture, protocol filtering, connectivity validation, and SIEM log review across Kali Linux and Windows virtual machines.
- **[Linux Web Infrastructure & TLS](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-25-Linux-Web-Infrastructure-and-Security-Configuration)** — Administered Ubuntu over SSH, deployed Nginx, managed services with systemd, and configured and validated HTTPS/TLS in a virtualized server environment.
- **[Active Directory Group-Based Access Control](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-04-Active-Directory-Access-Control)** — Implemented AD security-group-based authorization with NTFS and share permissions to demonstrate least privilege, resource access control, and enterprise IAM fundamentals.
- **[Windows Server 2022 RDP Configuration & Troubleshooting](https://github.com/johninfra/it-support-and-cybersecurity-labs/tree/main/Lab-20-Configuring-and-Troubleshooting-Remote-Desktop-Protocol-on-Windows-Server-2022)** — Configured and troubleshot remote administration on Windows Server 2022, including firewall rules, TCP/UDP 3389, connectivity validation, and structured root-cause troubleshooting.

## Technical Skills

| Area | Tools & practices |
| --- | --- |
| Cloud & Azure | Azure Virtual Networks, subnets, NSGs, RBAC, Azure Policy, remediation, resource locks, Cost Management, Azure Monitor, Activity Log alerts, Azure Static Web Apps, Azure Resource Manager REST APIs, Windows Server VMs, Azure CLI, Azure VM Run Command |
| Identity & access | Active Directory, Microsoft Entra ID, Microsoft Graph, MSAL.js, OAuth 2.0/PKCE, Microsoft Authenticator, MFA, security groups, group-based Azure RBAC, user provisioning/deprovisioning, effective-access validation, App Registrations, Enterprise Applications, OIDC, workload identity federation, Conditional Access, least privilege |
| Systems & endpoints | Windows 10/11, Windows Server 2022, Microsoft 365, Intune, Group Policy, Ubuntu, Kali Linux |
| Automation & administration | PowerShell, GitHub Actions CI/CD, Windows CMD, Linux CLI, RDP, SSH, VMware Workstation |
| Networking | TCP/IP, DNS, DHCP, VPN, SMB, Wireshark, Nmap |
| Security & monitoring | Splunk, SPL, Sysmon, Windows Event Logs, Microsoft Defender, endpoint security assessment |
| IT operations | Incident triage, ticket management, troubleshooting, escalation, technical documentation, SOP development |
