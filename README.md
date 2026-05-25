<div align="center">

# 👋 Welcome to My IT & Cybersecurity Portfolio

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1026,50:0078D4,100:00FF99&height=180&section=header&text=Chris%20Stoute&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />

## 🛡️ SOC Analyst | Threat Hunting | Incident Response | SIEM | Vulnerability Management | Security Automation

![Profile Views](https://komarev.com/ghpvc/?username=Chrisstoute&label=Profile%20Views&color=0e75b6&style=flat)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-SOC%20Analyst-blue)
![Microsoft Sentinel](https://img.shields.io/badge/SIEM-Microsoft%20Sentinel-5E5ADB)
![Microsoft Defender](https://img.shields.io/badge/XDR-Microsoft%20Defender-0078D4)
![Azure](https://img.shields.io/badge/Cloud-Microsoft%20Azure-0078D4)
![Tenable](https://img.shields.io/badge/Vulnerability%20Management-Tenable-red)
![PowerShell](https://img.shields.io/badge/Automation-PowerShell-5391FE)
![KQL](https://img.shields.io/badge/Query%20Language-KQL-00B7C3)
![Status](https://img.shields.io/badge/Status-Actively%20Building-success)

</div>

</div>

<div align="center">


<table>
<tr>
<td align="center">

<h3>🛡️ Cyber Range Scenario Credit 🛡️</h3>

<strong>All threat hunt scenarios, projects, and training were provided by Josh Madakor, CEO of The Cyber Range.</strong>

<br><br>

<a href="https://www.skool.com/cyber-range">
  <img src="https://img.shields.io/badge/JOIN%20THE%20CYBER%20RANGE-CLICK%20HERE-red?style=for-the-badge&labelColor=000000&color=ff0000" alt="Join The Cyber Range">
</a>

</td>
</tr>
</table>

</div>

## 🧭 About This Portfolio

The **Cyber Range Internship** helped me build a practical, job-ready cybersecurity portfolio focused on analyst-level workflows instead of theory alone. I worked through realistic scenarios involving suspicious activity detection, endpoint investigation, Azure activity monitoring, ransomware-style behavior, Linux compromise analysis, vulnerability management, and compliance remediation.

The projects I've completed are designed to simulate practical blue-team workflows: detecting suspicious activity, investigating telemetry, creating detection logic, documenting findings, containing incidents, validating remediation, and presenting results.

I have been working heavily with **Microsoft Sentinel, Microsoft Defender for Endpoint, AzureActivity logs, KQL, Tenable Vulnerability Management, PowerShell, Azure virtual machines, Windows/Linux hardening, and GitHub documentation**.

---

## 🚨 Featured Threat Hunting & SOC Projects
---
## 🛡️ DISA STIG Remediation Project

**Repository:** [DISA STIG Remediation Project](https://github.com/Chrisstoute/DISA-Stigs)

Completed 10 DISA STIG remediations against a Windows 11 virtual machine using Tenable compliance scanning, Local Group Policy, Local Security Policy, Registry Editor, PowerShell, and repeated validation scans. Each STIG remediation was documented in its own folder with screenshots, remediation scripts, before-and-after evidence, manual remediation references, and final Tenable pass validation.

**STIGs Completed:**

| # | STIG ID | Requirement | Status |
|---|---|---|---|
| 1 | WN11-AU-000500 | Application event log size must be configured to 32768 KB or greater | Completed |
| 2 | WN11-AU-000510 | System event log size must be configured to 32768 KB or greater | Completed |
| 3 | WN11-AU-000505 | Security event log size must hold at least one week of audit records | Completed |
| 4 | WN11-AC-000020 | Password history must be configured to 24 passwords remembered | Completed |
| 5 | WN11-AC-000035 | Minimum password length must be configured to 14 characters | Completed |
| 6 | WN11-AC-000010 | Number of allowed bad logon attempts must be configured to three or fewer | Completed |
| 7 | WN11-CC-000330 | WinRM client must not use Basic authentication | Completed |
| 8 | WN11-CC-000360 | WinRM client must not use Digest authentication | Completed |
| 9 | WN11-CC-000350 | WinRM service must not allow unencrypted traffic | Completed |
| 10 | WN11-CC-000270 | Remote Desktop Services must prevent users from saving passwords | Completed |

**Skills Demonstrated:**

- DISA STIG compliance analysis
- Tenable compliance scanning
- Windows 11 security hardening
- Local Group Policy configuration
- Local Security Policy configuration
- Windows Registry remediation
- PowerShell automation
- Event log configuration
- Account policy hardening
- WinRM security configuration
- Remote Desktop security configuration
- Before-and-after validation evidence
- Remediation documentation
- Git and GitHub project publishing

**Key Capabilities:**

- Identified failed DISA/STIG audit checks in Tenable.
- Reviewed STIG requirements and Tenable solution guidance.
- Performed manual remediation path review through Windows policy tools.
- Created repeatable PowerShell scripts for each remediation.
- Validated local settings using PowerShell, registry checks, `net accounts`, `gpupdate`, and `wevtutil`.
- Performed follow-up Tenable scans to confirm remediation success.
- Published each STIG as a standalone GitHub remediation folder.

---

## 👻 Ghost in the Stack — Advanced Threat Hunt

**Repository:** [Ghost in the Stack](https://github.com/Chrisstoute/Ghost-in-the-Stack)

Conducted an advanced multi-phase threat hunt against a simulated Linux intrusion on `GF-DEV01`. The investigation used Microsoft Sentinel, Microsoft Defender Advanced Hunting, KQL, Linux telemetry, shell history, file events, process execution data, network events, and service state evidence to reconstruct the full attacker lifecycle from initial access through implant deployment, persistence, lateral movement preparation, payload staging, and live-threat containment planning.

**Skills Demonstrated:**

- Microsoft Sentinel
- Microsoft Defender Advanced Hunting
- KQL
- Linux threat hunting
- Incident response investigation
- Process telemetry analysis
- File telemetry analysis
- Linux shell history analysis
- SSH authentication investigation
- Persistence detection
- Systemd service investigation
- Implant and C2 activity analysis
- Network enrichment and OSINT
- Containment planning
- SOC-style reporting and documentation

**Key Documentation:**

- [Walkthrough](https://github.com/Chrisstoute/Ghost-in-the-Stack/blob/main/docs/walkthrough.md)
- [Findings Summary](https://github.com/Chrisstoute/Ghost-in-the-Stack/blob/main/docs/findings-summary.md)
- [Lessons Learned](https://github.com/Chrisstoute/Ghost-in-the-Stack/blob/main/docs/lessons-learned.md)

---
### 🚢 Azuki Port of Entry Threat Hunt

**Repository:** [Azuki Port of Entry Threat Hunt](https://github.com/Chrisstoute/Port-of-Entry-Threat-Hunt)

Investigated a simulated compromise of an IT admin workstation for Azuki Import/Export after sensitive supplier contracts and pricing data were exposed. The hunt used Microsoft Defender for Endpoint Advanced Hunting and KQL to trace the full attack chain from initial access through persistence, credential dumping, data staging, exfiltration, defense evasion, and lateral movement.

**Skills Demonstrated:**

- Microsoft Defender for Endpoint
- Advanced Hunting
- KQL
- Incident response investigation
- Process, file, registry, and network telemetry analysis
- Initial access investigation
- Persistence detection
- Credential dumping analysis
- Data staging and exfiltration investigation
- Lateral movement analysis
- Windows event log clearing detection
- SOC-style reporting and documentation
---
### 🧨 PwnCrypt Ransomware Threat Hunt

**Repository:** [PwnCrypt Ransomware Threat Hunt](https://github.com/Chrisstoute/PwnCrypt-Ransomware-Threat-Hunt)

Simulated a zero-day ransomware investigation in Microsoft Defender for Endpoint using Advanced Hunting and KQL. The hunt focused on identifying ransomware-style file activity, suspicious PowerShell execution, affected files, process chains, network activity, and Defender telemetry.

**Skills Demonstrated:**

- Microsoft Defender for Endpoint
- Advanced Hunting
- KQL
- PowerShell command-line investigation
- File and process telemetry analysis
- Suspicious script execution analysis
- MITRE ATT&CK mapping
- Incident response documentation

---

### 🧯 Excessive Azure Resource Deletion Threat Hunt

**Repository:** [Excessive Azure Resource Deletion Threat Hunt](https://github.com/Chrisstoute/Excessive-Azure-Resource-Deletion-Threat-Hunt)

Built a Microsoft Sentinel detection and incident response workflow for excessive Azure resource deletion activity. The lab used AzureActivity logs to identify suspicious delete operations, summarize activity by caller, map entities, create a Sentinel analytics rule, trigger an incident, investigate the incident graph, document response actions, and close the incident as a true positive.

**Skills Demonstrated:**

- Microsoft Sentinel analytics rule creation
- AzureActivity log investigation
- KQL detection engineering
- Entity mapping
- Incident creation and alert grouping
- Sentinel investigation graph analysis
- Incident activity logging
- True positive incident closure
- MITRE ATT&CK: Impact / Data Destruction

---

### 🧅 Unauthorized TOR Usage Threat Hunt

**Repository:** [Unauthorized TOR Usage Threat Hunt](https://github.com/Chrisstoute/Unauthorized-TOR-Usage-Threat-Hunt)

Performed a Microsoft Defender for Endpoint threat hunt focused on identifying unauthorized TOR Browser installation and usage within an enterprise environment. The investigation used Advanced Hunting and KQL to detect TOR-related file activity, process execution, network connections, suspicious browsing behavior, and evidence of user-created files associated with dark web activity.

**Skills Demonstrated:**

- Microsoft Defender for Endpoint
- Advanced Hunting
- KQL
- DeviceFileEvents analysis
- DeviceProcessEvents analysis
- DeviceNetworkEvents analysis
- TOR browser detection
- Endpoint telemetry investigation
- Suspicious network activity analysis
- Timeline reconstruction
- Incident response documentation
- MITRE ATT&CK mapping

---

## 🛡️ Vulnerability Management Project

### Vulnerability Management Program Implementation

**Repository:** [Vulnerability Management Program](https://github.com/Chrisstoute/Vulnerability-Management-Program)

Designed and documented a vulnerability management lifecycle in Microsoft Azure using Tenable Vulnerability Management. The project included vulnerable Windows and Linux virtual machines, authenticated scans, prioritization, remediation, validation, and documentation.

**Key Capabilities:**

- Azure VM deployment
- Tenable vulnerability scanning
- Credentialed scan configuration
- Windows and Linux vulnerability validation
- PowerShell remediation scripting
- SMB, RDP, NTLM, SSL/TLS, FTP, and guest account hardening
- Remediation verification through rescanning
- Vulnerability lifecycle documentation

---

## 🧬 File Integrity Monitoring Project

### PowerShell File Integrity Monitoring Lab

**Repository:** [File Integrity Monitoring Lab](https://github.com/Chrisstoute/File-Integrity-Monitoring-Lab)

Built a PowerShell-based File Integrity Monitoring system to detect unauthorized file modifications using SHA256 hashing, baseline comparison, multi-file monitoring, and security event logging.

**Key Capabilities:**

- SHA256 hash baseline generation
- File modification detection
- Multi-file and directory monitoring
- Security event logging
- Attacker attribution using host/user context
- PowerShell automation
- SOC-style alerting workflow

---

## ☁️ Azure SIEM Honeypot Project

**Repository:** [Azure SIEM Honeypot Lab](https://github.com/Chrisstoute/Azure-Siem-Honeypot-Lab)

Deployed a cloud-based honeypot in Microsoft Azure to capture and analyze attack traffic using Microsoft Sentinel, Log Analytics Workspace, Windows event logs, KQL, and geo-enriched attack visualization.

**Skills Demonstrated:**

- Microsoft Azure
- Microsoft Sentinel
- Log Analytics Workspace
- KQL querying
- Windows Security Event Logs
- Event ID 4625 analysis
- GeoIP enrichment
- Attack map visualization
- NSG exposure and monitoring

---

## 🧰 Technical Skills & Tools

```text
SIEM / XDR
[+] Microsoft Sentinel
[+] Microsoft Defender for Endpoint
[+] Advanced Hunting
[+] Log Analytics Workspace
[+] Elastic Stack SIEM

Querying & Detection
[+] KQL
[+] Detection engineering
[+] IOC scoping
[+] Alert tuning
[+] Entity mapping
[+] MITRE ATT&CK mapping

Incident Response
[+] Detection and analysis
[+] Containment planning
[+] Eradication recommendations
[+] Recovery documentation
[+] Post-incident activity logging
[+] True positive / false positive classification

Vulnerability Management
[+] Tenable Vulnerability Management
[+] Credentialed vulnerability scanning
[+] Remediation validation
[+] Risk prioritization
[+] Windows and Linux hardening

Cloud & Infrastructure
[+] Microsoft Azure
[+] Virtual machines
[+] NSGs
[+] Virtual networks
[+] Public IPs
[+] Resource groups
[+] AzureActivity logs

Automation & Scripting
[+] PowerShell
[+] Bash / Linux commands
[+] Git and GitHub
[+] Visual Studio Code
[+] Markdown documentation
```

---

## 🧠 Current Learning Focus

- Microsoft Sentinel incident response workflows
- KQL detection engineering
- Microsoft Defender for Endpoint investigations
- Threat hunting methodology
- Azure security monitoring
- Vulnerability management operations
- PowerShell automation for security tasks
- SOC analyst interview readiness
- GitHub portfolio documentation

---
## 🎯 Final Portfolio Reflection

Completing this internship was a long and challenging process, but it gave me hands-on experience that directly aligns with SOC analyst, security analyst, vulnerability management, and incident response responsibilities. Each project forced me to think like an analyst: gather evidence, validate assumptions, understand the risk, take action, and document the outcome clearly.

This internship strengthened my confidence in:

```text
Reading and interpreting security findings
Writing KQL queries
Investigating endpoint activity
Using SIEM and XDR tools
Working through vulnerability remediation
Automating Windows security fixes
Documenting technical work for a professional audience
Explaining my process clearly for interviews
```

---

## 🚀 Completed Cyber Range Internship Portfolio

This portfolio now represents a complete hands-on cybersecurity learning path covering:

- SOC investigations
- Threat hunting
- Incident response
- Azure monitoring
- Endpoint telemetry analysis
- Vulnerability management
- Compliance remediation
- PowerShell automation
- Professional GitHub reporting

---

## 📌 Portfolio Goals

My goal is to continue building practical cybersecurity projects that show the full workflow of a security analyst:

```text
Detect suspicious activity
Investigate the evidence
Scope affected users, hosts, and resources
Map behavior to MITRE ATT&CK
Recommend containment and remediation
Document the incident clearly
Create repeatable detections
Publish professional GitHub write-ups
```

---

## 🤝 Connect With Me

<div align="center">

💼 <a href="https://www.linkedin.com/in/chris-stoute-157040164/">Connect with me on LinkedIn</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF99,50:0078D4,100:0B1026&height=120&section=footer" />

</div>
