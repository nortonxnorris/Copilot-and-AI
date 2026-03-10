# Get started with DSPM in Purview

## Overview
Microsoft Purview Data Security Posture Management (DSPM) helps organizations discover, protect, and investigate sensitive data risks across their digital estate.
It consolidates insights from the Microsoft Purview solutions such as Data Loss Prevention (DLP), Insider Risk Management, and Information Protection.


### Prerequisites
> The tasks below are in the list of setup tasks

**Required**
- Purview Audit enabled
- Permissions: Compliance Administrator

**Recommended**
- Sensitivity labels in Purview Information Protection
- Onboard devices to Purview and install browser extensions
- Entra registered app with permissions for item level scanning
- Setup Purview for Pay as you go (PAYG)


## Navigating DSPM

### Posture
- View key posture metrics such as: Agent interactions, Data oversharing, Copilot interactions
### Objectives
- Each objective offers a dashboard, and a recommended remediation plan
### AI Observability
- Inventory of AI apps with activity in the last 30 days
### Discover
- Data Risk Assessments - Identify potentially overshared items and remediate (ex: apply a label or remove a sharing link)
### Tasks and Actions
- Setup tasks are listed by type: Required and Recommended
- Select a recommended task to view details such as PAYG requirements, or policies included in the recommendation
- Offers a single-click option to create polices
### Reports
- Use filters to narrow down the reports based on categories such as Exfiltration, Oversharing, AI, Data Discovery, Labeling protection and DLP


## Reference Resources
- Microsoft Learn: https://learn.microsoft.com/en-us/purview/data-security-posture-management-learn-about
- Permissions: https://learn.microsoft.com/en-us/purview/data-security-posture-management-permissions
- Item level scan permissions: https://learn.microsoft.com/en-us/purview/dspm-for-ai-considerations#prerequisites-for-microsoft-365-item-level-scanning-for-data-risk-assessments
- Enable PAYG: https://learn.microsoft.com/en-us/purview/purview-payg-subscription-based-enablement
