# ☁️ Hi, I'm Neche — Microsoft Systems & Azure Administration

IT Analyst specializing in **Microsoft endpoint, identity, and Azure administration** — Active Directory, Entra ID, Intune, and PowerShell automation across a 200+ user environment. Building toward **Azure Cloud Administrator / Engineer**, one documented lab at a time.

> Each lab recreates a task a sysadmin or Azure administrator owns in production — built in the portal, automated in PowerShell, then codified as infrastructure-as-code. Scripts, screenshots, and honest troubleshooting included.

---

## 🏆 Certifications

- **CompTIA:** Security+ · A+ · Network+
- **Microsoft:** [Azure Fundamentals (AZ-900)](https://www.credly.com/badges/ed481e36-d85c-4bc2-8a92-105b6a120e94/public_url)
- **AWS:** Certified Cloud Practitioner
- **Other:** ITIL v4 Foundation · Linux Essentials · [Cisco Introduction to Cybersecurity](https://www.credly.com/badges/bc46596b-060a-4e4c-9461-baa34c25d47b/public_url)
- 🎯 **In progress:** AZ-104 — Microsoft Azure Administrator

---

## 🧰 Core Skills

| Domain | Technologies & Capabilities |
|---|---|
| **Windows / Directory** | Active Directory (AD DS), Group Policy (GPO), DNS/DHCP, Windows Server 2019/2022/2025, file-server NTFS/RBAC |
| **Hybrid Identity** | Microsoft Entra ID, Entra Connect (PHS), Seamless SSO, Conditional Access, MFA, SSPR, RBAC |
| **Azure Core** | Virtual Machines, VNets/NSGs, Storage, Azure Policy, Azure Monitor, Sentinel, Log Analytics |
| **Endpoint** | Microsoft Intune (MDM/MAM), compliance policies, app deployment, SCCM/MECM, Autopilot |
| **Automation & IaC** | PowerShell, Microsoft Graph, KQL · *Terraform · Ansible · Bicep — in progress* |

---

## 👨‍💻 Projects

### 🌐 Hybrid Windows Server 2025 & Entra ID Lab

**Objective:** Build a corporate hybrid environment — on-prem Active Directory synced to the cloud — the way a systems administrator stands one up in production.

**Impact:** Deployed a Windows Server 2025 domain controller with a departmental OU structure, security groups, and an NTFS/RBAC file server (Finance/HR/Public shares with verified cross-department deny). Enforced password/lockout policies and automated H: drive mapping via GPO with item-level targeting, then synced 8 users to Microsoft Entra ID through Entra Connect (Password Hash Sync, Seamless SSO, OU filtering, password writeback). Documented four real troubleshooting fixes.

**Skills:** Windows Server 2025 · AD DS · GPO · NTFS/RBAC · Entra Connect · Hybrid Identity · SSO · PowerShell

📁 [Hybrid Windows Server & Entra ID Lab](https://github.com/Necheogbu7/2025serverLab)

---

### 💻 Microsoft Intune, Identity & Endpoint Security Lab

**Objective:** Manage a cloud-joined Windows endpoint end to end — from identity and enrollment through compliance and app delivery.

**Impact:** Built the full Intune lifecycle in a live Entra ID tenant: IAM users and security groups with RBAC and enforced MFA, Windows 10 enrollment via Company Portal, password + encryption compliance policies, and auto-deployed M365 apps to compliant-device groups — validated through Entra sign-in and audit logs.

**Skills:** Microsoft Intune · Entra ID · RBAC · MFA · Compliance Policies · App Deployment · M365 Admin

📁 [Intune / IAM / Endpoint Security Lab](https://github.com/Necheogbu7/Intune)

---

### 🛡️ Azure Sentinel SIEM — Failed RDP Geolocation Map

**Objective:** Operate a cloud SIEM against live attack traffic and turn raw event logs into a geospatial threat map.

**Impact:** Deployed Azure Sentinel over a Log Analytics workspace and exposed a honeypot VM to capture real-world RDP brute-force attempts. Wrote a PowerShell script that parses failed-logon events and enriches each with IP geolocation data, then used KQL to build a custom table and plotted global attack origins on a Sentinel workbook map.

**Skills:** Azure Sentinel · Log Analytics · KQL · PowerShell · SIEM · Threat Monitoring

📁 [Azure Sentinel SIEM Project](https://github.com/Necheogbu7/sentinalproject) · 📺 [Walkthrough](https://youtu.be/OO8kANl7fcw)

---

## 🗺️ Roadmap (building in public)

Weekly labs toward AZ-104 and Azure administration — each built portal → PowerShell → Terraform:

✅ AD DS & GPO → ✅ Hybrid Identity → PowerShell provisioning → **Azure Compute → Networking → Storage → RBAC & Policy → Monitoring → Backup/Recovery** → Intune + Autopilot → Graph automation → **IaC capstone (Terraform + Ansible + CI/CD)**.

---

## 📫 Connect

- **LinkedIn:** [chinecheremogbunwobodo](https://linkedin.com/in/chinecheremogbunwobodo)
