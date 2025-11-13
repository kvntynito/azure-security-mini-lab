## Azure Cloud Security

This project demonstrates hands-on cloud security skills inside Microsoft Azure.
It includes Azure security reviews, Sentinel analyses, IAM evaluations, architecture mapping, and evidence from a real mini-lab using Azure free-tier resources.

## 🎯 Objectives
- Azure Security Review
- Sentinel screenshots
- Defender for Cloud findings
- Key Vault security notes
- IAM / RBAC analysis

## 📁 What’s Inside
- `docs/` – reports, playbooks, baselines, diagrams
- `scripts/` – Python/PowerShell/Bash utilities
- `lab/` – sample logs, datasets, IaC
- `.github/` – issue/PR templates

## 🧪 Lab Setup (Quick Start)
This lab uses a small Azure environment created using the Azure free tier, making it easy to replicate.

✅ **Azure Resources Used**
- **Azure AD / Entra ID**
  - Users, groups, role assignments
  - Conditional Access (optional)
- **Log Analytics Workspace**
  - Central log storage
  - Sentinel data ingestion
- **Microsoft Sentinel**
  - Analytics rules
  - Incidents
  - Hunting queries
- **Defender for Cloud**
  - Secure Score
  - Recommendations
  - Regulatory Compliance baseline
- **Optional resources**
  - Virtual Machines
  - Storage Accounts
  - Key Vault
  - App Services

## ☁️ Cloud Security Focus Areas
✅ **Identity Security (Entra ID)**
- MFA enforcement
- Role-based access control (RBAC)
- Privileged roles review
- Conditional Access testing
- Sign-in logs analysis

✅ **Microsoft Sentinel**
- Analytics rules
- Basic detections
- Incident investigation
- Hunting queries (KQL)
- Connecting data sources

✅ **Defender for Cloud**
- Secure Score improvement
- Resource configuration review
- Recommendations export
- Comparison before/after
  
✅ **Azure Resource Security**
- Storage account hardening
- Network security groups
- Key Vault access policies
- VM baseline assessment

## ▶️ How to Run (Lab Steps)
✅ **1. Create or use Azure free account**
Spin up:
- 1 VM
- 1 Log Analytics Workspace
- 1 Sentinel instance
- Basic identity setup

✅ **2. Connect security data sources**
Enable:
- Azure activity logs
- Sign-in logs
- Defender for Cloud
- Sysmon logs (optional if VM used)

✅ **3. Review posture with Defender for Cloud**

Export:
- Secure Score
- Recommendations
- Compliance baseline

Save screenshots in /lab/.

✅ **4. Test Sentinel detections**

Examples:
- Failed login attempts
- RDP brute force
- Suspicious PowerShell commands

Save alerts + queries.

✅ **5. Document the findings**

Fill in:
- docs/Azure_Security_Review_TEMPLATE.md
- docs/Architecture_Diagram_TEMPLATE.md
- docs/Incident_Report_TEMPLATE.md (if you trigger incidents)

## 📊 Deliverables

✅ Azure security review report

✅ Defender for Cloud Secure Score results

✅ Sentinel alerts & incident investigations

✅ KQL queries

✅ Architecture diagram of your Azure setup

✅ Screenshots of IAM, policies, NSGs, logs

✅ Optional automation scripts

## 🧠 What I Learned
- Bullet points of concepts/skills you gained - Write what you learned about identity, cloud posture, Sentinel.
- How Azure manages identity using Entra ID
- How cloud logging differs from on-prem logs
- How Microsoft Sentinel ingests, normalizes, and correlates data
- How to use KQL for threat hunting and detections
- How Secure Score reflects overall cloud posture
- How to apply zero-trust principles in Azure
- How to evaluate cloud resources against security best practices

## ✅ Next Steps

- Add custom KQL detection rules
- Integrate Azure AD Identity Protection alerts
- Configure Logic Apps for automated response (SOAR)
- Add Key Vault access monitoring
- Expand to multi-cloud comparison (AWS or GCP)
- Add exportable ARM/Bicep templates for reproducible labs

## ⚖️ License
MIT – see `LICENSE`.
