# Gabriel Marquez - Cybersecurity Operations, Detection Engineering, and AI Security

Bilingual cybersecurity professional with 8+ years of remote endpoint troubleshooting, technical triage, remediation support, PowerShell automation, documentation, and playbook-driven operations experience.

Recently completed an M.S. in Cybersecurity & Information Assurance and built public security projects focused on SIEM detection engineering, analyst workflows, vulnerability prioritization, Azure cloud security governance, and AI/Web3 tool-boundary security research.

## Core Strengths

- Security operations and endpoint triage
- SIEM-style alert analysis and detection workflow documentation
- Splunk SOC workflows: SPL triage, ingestion validation, dashboards, parsing repair, and field extraction
- Detection logic mapped to MITRE ATT&CK
- Analyst playbooks and repeatable investigation workflows
- Azure cloud security governance and control documentation
- Vulnerability prioritization using EPSS, CISA KEV, NVD, and CVSS context
- PowerShell and Python automation for security workflows
- AI/tool-boundary security research
- Bilingual Spanish/English technical communication

---

# Portfolio Proof Map

Start here if reviewing quickly.

| Project | What It Proves | Best Fit |
|---|---|---|
| [Elastic SIEM Detection Engineering & Vulnerability Risk Automation](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization) | Detection engineering, Elastic SIEM validation, analyst playbooks, alert evidence, MITRE mapping, and CVE prioritization automation. | SOC Analyst, Security Analyst, MDR Analyst, SIEM Analyst, Detection Analyst, Vulnerability Analyst |
| [Azure Cloud Security Governance](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance) | Azure RBAC scope, Key Vault recovery protection, Azure Policy tag governance, Recovery Services backup policy, NIST-aligned control mapping, risk register discipline, and sanitized evidence screenshots. | Cloud Security Analyst, Information Security Analyst, Azure Security, GRC-adjacent cloud security, MSSP/Microsoft-aligned roles |
| [Empire Breacher](https://github.com/gabrielmarquezcyber/empire-breacher) | AI/Web3 wallet-agent security research, prompt-injection testing, authority-boundary validation, PASS/REVIEW/FAIL evaluation, OWASP/MITRE ATLAS mapping, and agent-behavior safety analysis. | AI Security, AppSec, Product Security, Web3 Security, LLM/agent security, security research |
| [SOC Analyst Splunk Operations Workbook](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook) | Splunk SOC analyst workflows, SPL triage, log ingestion validation, reports, dashboards, alert-candidate logic, parsing repair, masked field analysis, custom field extraction, and network-log analysis through a visual proof narrative. | SOC Analyst, MDR Analyst, SIEM Analyst, Security Operations Analyst, Splunk Analyst, Log Analysis, Security Monitoring |

---

# Featured Security Projects

## 1. Elastic SIEM Detection Engineering & Vulnerability Risk Automation

A cybersecurity portfolio project focused on SOC-style detection workflows, alert validation, analyst documentation, and risk-based vulnerability prioritization.

This project demonstrates how security telemetry and vulnerability intelligence can be turned into practical analyst workflows.

### What it demonstrates

- Built and validated Elastic SIEM detection rules.
- Created Suspicious PowerShell Flags detection mapped to MITRE ATT&CK T1059.001.
- Created Failed Logon Burst detection using Windows Event ID 4625 mapped to MITRE ATT&CK T1110.
- Developed analyst-facing playbooks with investigation steps, escalation context, and evidence handling.
- Exported detection logic as reproducible NDJSON rules.
- Captured Elastic validation screenshots and alert evidence.
- Built Python CVE prioritization automation using EPSS, CISA KEV, NVD, and CVSS data.
- Generated ranked CVE outputs and prioritization graphics for remediation planning.

### Review this project

- [Repository](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization)
- [Suspicious PowerShell Flags rule](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/rules/Suspicious_PowerShell_Flags_EQL.ndjson)
- [Failed Logon Burst rule](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/rules/failed_logon_burst.ndjson)
- [Suspicious PowerShell playbook](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/playbooks/playbook_suspicious_powershell_flags.md)
- [Failed Logon Burst playbook](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/playbooks/playbook_failed_logon_burst_4625.md)
- [CVE prioritization script](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/scripts/cve_prioritizer.py)

### Relevant roles

SOC Analyst, Security Analyst, MDR Analyst, SIEM Analyst, Detection Analyst, Vulnerability Analyst, Security Operations Analyst, and detection-engineering-adjacent roles.

---

## 2. Azure Cloud Security Governance

A public Azure cloud security governance portfolio project for a simulated regulated environment.

This project documents how Azure configuration choices can be mapped to security objectives, control families, risk findings, and audit-defensible evidence.

### What it demonstrates

- Department-scoped Azure RBAC and least-privilege access reasoning.
- Azure Key Vault soft delete and purge protection.
- Azure Policy Department tag governance for ownership and accountability.
- Recovery Services backup policy schedule and retention documentation.
- NIST SP 800-53 control-family alignment.
- PCI/FISMA-oriented governance notes without claiming formal certification.
- Risk register findings with impact, mitigation, and residual risk.
- Sanitized Azure screenshots used as public evidence.

### Review this project

- [Repository](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance)
- [Evidence summary](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance/blob/main/docs/evidence-summary.md)
- [Control mapping](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance/blob/main/docs/control-mapping.md)
- [Risk register](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance/blob/main/docs/risk-register.md)

### Relevant roles

Cloud Security Analyst, Information Security Analyst, Security Analyst, Azure Security, GRC-adjacent cloud security, Microsoft security operations, and MSSP/Microsoft-aligned roles.

---

## 3. Empire Breacher - AI/Web3 Wallet-Agent Security Research Harness

A controlled AI/Web3 security research project focused on prompt-injection risk, authority-boundary failures, and safe behavior validation in wallet-enabled agent workflows.

This project models how untrusted external content should be analyzed without allowing that content to authorize high-impact wallet behavior.

### What it demonstrates

- Built a controlled wallet-agent security research harness.
- Modeled prompt-injection and authority-boundary risk in lab conditions.
- Implemented deterministic PASS / REVIEW / FAIL evaluation.
- Created malicious, ambiguous, and benign wallet-agent fixtures.
- Built a toy wallet-agent simulator.
- Enforced the invariant that external content can be analyzed but cannot authorize wallet behavior.
- Added fixture evaluation tooling, validation reports, safety policy documentation, and project roadmap.
- Added threat framework and detection mapping using OWASP LLM Top 10 and MITRE ATLAS concepts.

### Review this project

- [Repository](https://github.com/gabrielmarquezcyber/empire-breacher)
- [Project roadmap](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/ROADMAP.md)
- [Phase 3 validation report](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/validation-reports/phase-3-wallet-agent-evaluation.md)
- [Threat framework and detection mapping](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/lab-notes/threat-framework-detection-mapping-001.md)

### Relevant roles

AI Security, AppSec, Product Security, Web3 Security, LLM/agent security, prompt injection, automation security, security research, and forward-looking security operations roles involving AI-assisted workflows.

---

# Supporting Security Field Notes

Short defender-focused artifacts from hands-on labs and technical research. These supporting notes show practical security learning, validation logic, troubleshooting discipline, and how offensive techniques map to defensive understanding.

## SOC Analyst Splunk Operations Workbook

A reviewer-facing Splunk SOC operations artifact demonstrating practical SIEM analyst workflows, SPL search logic, log ingestion validation, reporting, dashboarding, parsing repair, custom field extraction, and network-log analysis.

This project does not claim production Splunk administration experience. It demonstrates hands-on Splunk analyst and configuration workflow in a controlled lab environment, with embedded screenshot evidence and supporting SPL/config files.

### What it demonstrates

- SPL triage searches for SOC-style investigation workflows
- Lookup enrichment, iplocation enrichment, eventstats, threshold logic, and baseline/anomaly-style reasoning
- Splunk Enterprise startup, index creation, listener/forwarder concepts, and log ingestion validation
- Linux authentication log and Apache access log ingestion
- Reports, dashboard panels, and alert-candidate SPL
- Custom Splunk app structure and scripted input documentation
- inputs.conf, props.conf, transforms.conf, and fields.conf workflow documentation
- Event boundary repair, multiline parsing, SEDCMD masking, and custom field extraction
- Safe masked field analysis and validation searches
- Applied network-log parsing repair and network activity analysis

### Review this field note

- [Repository](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook)
- [Main visual README](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook)
- [Reviewer proof map](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook/blob/main/reviewer-proof-map.md)
- [Docs index](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook/tree/main/docs)

### Relevant roles

SOC Analyst, MDR Analyst, SIEM Analyst, Splunk Analyst, Security Operations Analyst, Security Monitoring Analyst, Log Analysis Analyst, Detection Analyst, and MSSP roles involving Splunk, SPL, dashboards, reports, parsing, field extraction, or log ingestion.

---

## Active Directory Persistence - Defender-Focused Field Notes

A defender-focused Active Directory persistence artifact covering identity, trust, permissions, group inheritance, and policy-based persistence mechanisms in a controlled lab environment.

### What it demonstrates

- AD CS certificate-based persistence
- SIDHistory privilege paths
- Nested group privilege inheritance
- AdminSDHolder / SDProp ACL propagation
- GPO logon-script persistence
- DCSync, Golden Ticket, and Silver Ticket persistence concepts
- Defender validation logic after suspected domain compromise
- Sanitized screenshot evidence, technique mapping, and troubleshooting notes

### Review this field note

- [Repository](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes)
- [Defender validation checklist](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/defender-validation-checklist.md)
- [Technique matrix](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/technique-matrix.md)
- [Troubleshooting notes](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/troubleshooting-notes.md)

### Relevant roles

SOC Analyst, MDR Analyst, Security Analyst, Incident Response, Identity Security, Active Directory security, Windows enterprise security, and threat hunting roles involving persistence or lateral movement.

---

# Technical Discussion Topics

- Alert triage and false-positive review
- Suspicious PowerShell behavior and dual-use tooling
- Failed logon burst detection and brute-force / password-spray logic
- MITRE ATT&CK mapping for analyst communication
- Analyst playbook design and evidence documentation
- Elastic SIEM rule validation and alert evidence
- Splunk SPL triage, lookup enrichment, iplocation, eventstats, and alert-candidate logic
- Splunk ingestion validation, index creation, reports, dashboards, and analyst-facing visual evidence
- Splunk parsing repair using props.conf, transforms.conf, fields.conf, SEDCMD masking, and custom field extraction
- Linux auth log, Apache access log, and network-log analysis in Splunk
- Azure RBAC scope and least-privilege governance
- Azure Key Vault recovery protections
- Azure Policy tag governance
- Backup policy documentation and recovery-readiness reasoning
- NIST SP 800-53 control-family mapping
- Python-based CVE prioritization
- EPSS, CISA KEV, NVD, and CVSS-based remediation prioritization
- AI/tool-boundary safety principles
- Bilingual Spanish/English technical communication in support and security operations contexts

---

# Links

- LinkedIn: [linkedin.com/in/gabriel-marquez-cyber](https://www.linkedin.com/in/gabriel-marquez-cyber/)
- Elastic SIEM Detection Engineering: [github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization)
- Azure Cloud Security Governance: [github.com/gabrielmarquezcyber/azure-cloud-security-governance](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance)
- Empire Breacher: [github.com/gabrielmarquezcyber/empire-breacher](https://github.com/gabrielmarquezcyber/empire-breacher)
- SOC Analyst Splunk Operations Workbook: [github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook)
- Public Resume: [Gabriel Marquez - Cybersecurity Resume](resume/Gabriel_Marquez_Public_Cybersecurity_Resume.md)
