# Gabriel Marquez - Cybersecurity Operations, SIEM, Vulnerability Risk, and Cloud Security Governance

Bilingual cybersecurity professional with an M.S. in Cybersecurity & Information Assurance, SecurityX, CySA+, PenTest+, and 8+ years of remote technical operations, escalation, remediation support, documentation, and playbook-driven troubleshooting experience.

Current target roles: SOC Analyst, Security Analyst, MDR Analyst, SIEM Analyst, Vulnerability Analyst, Information Security Analyst, Cloud Security Analyst, and GRC-adjacent cloud security roles.

## Certifications and Education

- M.S. Cybersecurity & Information Assurance
- B.S. Network Operations & Security
- SecurityX
- CySA+
- PenTest+
- ISC2 CC
- Project+

---

# Portfolio Proof Map

Fast reviewer path.

| Review Need | Start Here | Why |
|---|---|---|
| Primary SOC / detection proof | [Elastic SIEM Detection Engineering & Vulnerability Risk Automation](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization) | Strongest defensive security artifact: detection validation, MITRE mapping, analyst playbooks, evidence capture, and Python vulnerability prioritization. |
| Cloud security / governance proof | [Azure Cloud Security Governance](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance) | Best cloud/GRC complement: RBAC, Key Vault recovery protection, Azure Policy, backup readiness, risk register, and control mapping. |
| SOC workbook depth | [Elastic and Wazuh Detection Operations Workbook](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook) | Logstash ingestion, Wazuh rule troubleshooting, KQL/Lucene investigation, and Apache log attack reconstruction. |
| Splunk / SIEM workflow proof | [SOC Analyst Splunk Operations Workbook](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook) | SPL triage, ingestion validation, dashboards, parsing repair, masking, field extraction, and network-log analysis. |
| Windows identity / persistence literacy | [Active Directory Persistence - Defender-Focused Field Notes](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes) | Defender-focused validation logic for AD CS, SIDHistory, nested groups, AdminSDHolder/SDProp, GPO logon scripts, and Kerberos trust abuse. |
| AI / agent security research | [Empire Breacher](https://github.com/gabrielmarquezcyber/empire-breacher) | Controlled AI/Web3 wallet-agent research focused on prompt injection, authority boundaries, PASS/REVIEW/FAIL behavior, and abuse-case analysis. |
| Writing and risk communication | [Cybersecurity Writing Portfolio](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio) | Published security writing, labor-market analysis, source discipline, and public communication. |

---

# Primary Portfolio Pillars

## 1. Elastic SIEM Detection Engineering & Vulnerability Risk Automation

A cybersecurity portfolio project focused on SOC-style detection workflows, alert validation, analyst documentation, and risk-based vulnerability prioritization.

This is the strongest current technical proof artifact for SOC, MDR, SIEM, Detection Analyst, and Vulnerability Analyst roles.

### What it demonstrates

- Elastic SIEM detection rule creation and validation.
- Suspicious PowerShell behavior detection.
- Failed logon burst detection using Windows Event ID 4625.
- MITRE ATT&CK mapping.
- Analyst-facing playbooks.
- Evidence screenshots and alert validation.
- Python CVE prioritization using EPSS, CISA KEV, NVD, and CVSS context.
- Risk-based remediation prioritization.

### Business / SOC value

- Reduces alert ambiguity.
- Turns detections into triage steps.
- Connects evidence to analyst decision-making.
- Helps prioritize remediation beyond raw severity.

### Review this project

- [Repository](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization)
- [Suspicious PowerShell rule](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/rules/Suspicious_PowerShell_Flags_EQL.ndjson)
- [Failed Logon Burst rule](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/rules/failed_logon_burst.ndjson)
- [Suspicious PowerShell playbook](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/playbooks/playbook_suspicious_powershell_flags.md)
- [Failed Logon Burst playbook](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/playbooks/playbook_failed_logon_burst_4625.md)
- [CVE prioritization script](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization/blob/main/artifacts/scripts/cve_prioritizer.py)

### Best-fit roles

SOC Analyst, Security Analyst, MDR Analyst, SIEM Analyst, Detection Analyst, Vulnerability Analyst, and Security Operations Analyst.

---

## 2. Azure Cloud Security Governance

A public Azure cloud security governance portfolio project for a simulated regulated environment.

This project documents how Azure configuration choices can be mapped to security objectives, control families, risk findings, and audit-defensible evidence.

### What it demonstrates

- Department-scoped Azure RBAC and least-privilege access reasoning.
- Azure Key Vault soft delete and purge protection.
- Azure Policy Department tag governance.
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

### Best-fit roles

Cloud Security Analyst, Information Security Analyst, Security Analyst, Azure Security, GRC-adjacent cloud security, Microsoft security operations, and MSSP/Microsoft-aligned roles.

---

# Supporting SOC Workbooks and Security Field Notes

## Elastic and Wazuh Detection Operations Workbook

A reviewer-facing Elastic and Wazuh SOC operations workbook covering Logstash ingestion, Wazuh rule engineering, KQL/Lucene investigation patterns, and Apache log attack reconstruction.

Best reviewed for: SOC Analyst, SIEM Analyst, MDR Analyst, Detection Analyst, Wazuh, Elastic, and Logstash roles.

### What it demonstrates

- Logstash pipeline configuration for Linux authentication log ingestion.
- Grok parsing and timestamp normalization.
- Kibana validation of parsed authentication events.
- Wazuh decoder inspection and custom alert-rule engineering.
- Field-level troubleshooting when detection logic breaks.
- Corrected Wazuh rule validation after decoded-field inspection.
- KQL and Lucene investigation patterns.
- Web-application attack reconstruction from Apache log evidence.
- Sanitized screenshots, query ledgers, source files, and reviewer proof map.

### Review this workbook

- [Repository](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook)
- [Reviewer proof map](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook/blob/main/reviewer-proof-map.md)
- [Docs index](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook/blob/main/docs/README.md)
- [Wazuh rule troubleshooting](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook/blob/main/docs/02-wazuh-custom-alert-rule-engineering.md)
- [Slingshot attack reconstruction](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook/blob/main/docs/04-slingshot-attack-reconstruction.md)

---

## SOC Analyst Splunk Operations Workbook

A reviewer-facing Splunk SOC operations artifact demonstrating practical SIEM analyst workflows, SPL search logic, log ingestion validation, reporting, dashboarding, parsing repair, custom field extraction, and network-log analysis.

Tags: Splunk, SPL, Log Ingestion, Parsing Repair, Dashboards, SOC Workflow.

### What it demonstrates

- SPL triage searches for SOC-style investigation workflows.
- Lookup enrichment, iplocation enrichment, eventstats, threshold logic, and baseline/anomaly-style reasoning.
- Splunk Enterprise startup, index creation, listener/forwarder concepts, and log ingestion validation.
- Linux authentication log and Apache access log ingestion.
- Reports, dashboard panels, and alert-candidate SPL.
- Custom Splunk app structure and scripted input documentation.
- Event boundary repair, multiline parsing, SEDCMD masking, and custom field extraction.
- Safe masked field analysis and validation searches.
- Applied network-log parsing repair and network activity analysis.

### Review this workbook

- [Repository](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook)
- [Reviewer proof map](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook/blob/main/reviewer-proof-map.md)
- [Docs index](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook/blob/main/docs/README.md)

---

## Active Directory Persistence - Defender-Focused Field Notes

A defender-focused Active Directory persistence artifact covering identity, trust, permissions, group inheritance, and policy-based persistence mechanisms in a controlled lab environment.

### What it demonstrates

- AD CS certificate-based persistence awareness.
- SIDHistory privilege path validation.
- Nested group privilege inheritance.
- AdminSDHolder / SDProp ACL propagation.
- GPO logon-script persistence.
- DCSync, Golden Ticket, and Silver Ticket persistence concepts.
- Defender validation logic after suspected domain compromise.
- Sanitized screenshot evidence, technique mapping, and troubleshooting notes.

### Defender validation path

- Check replication rights.
- Check KRBTGT exposure and reset status.
- Check AD CS template and CA exposure.
- Check SIDHistory.
- Check nested privileged groups.
- Check AdminSDHolder / SDProp.
- Check GPO logon scripts.

### Review this field note

- [Repository](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes)
- [Defender validation checklist](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/defender-validation-checklist.md)
- [Technique matrix](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/technique-matrix.md)
- [Troubleshooting notes](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes/blob/main/docs/troubleshooting-notes.md)

---

# Featured Research: AI and Agent Security

## Empire Breacher

A controlled AI/Web3 wallet-agent security research harness focused on prompt-injection testing, authority-boundary validation, PASS/REVIEW/FAIL behavior evaluation, and abuse-case analysis for agentic systems.

This is a research artifact, not the primary SOC/GRC pillar.

### What it demonstrates

- AI/agent security research.
- Adversarial testing mindset.
- Authority-boundary validation.
- Prompt-injection and unsafe instruction analysis.
- PASS/REVIEW/FAIL behavior evaluation.
- OWASP LLM and MITRE ATLAS mapping concepts.
- Abuse-case analysis for tool-enabled AI systems.

### Review this research

- [Repository](https://github.com/gabrielmarquezcyber/empire-breacher)
- [Project roadmap](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/ROADMAP.md)
- [Phase 3 validation report](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/validation-reports/phase-3-wallet-agent-evaluation.md)
- [Threat framework and detection mapping](https://github.com/gabrielmarquezcyber/empire-breacher/blob/main/docs/threat-framework-and-detection-mapping.md)

---

# Writing and Security Analysis

A supporting proof area for published cybersecurity writing, labor-market analysis, source discipline, and public risk communication.

## Cybersecurity Writing Portfolio

### Current published work

| Work | Focus | Links |
|---|---|---|
| Making Competence Inspectable | Cybersecurity hiring, labor-market structure, proof-building, and why serious public artifacts matter. | [Essay](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio/blob/main/essays/001-making-competence-inspectable.md) / [Sources](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio/blob/main/sources/001-making-competence-inspectable-sources.md) / [Spanish](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio/blob/main/essays/001-making-competence-inspectable-es.md) |

### Review this writing portfolio

- [Repository](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio)

### What it demonstrates

- Clear cybersecurity writing and analysis.
- Labor-market and career strategy analysis.
- Source-backed public writing.
- Security communication that complements the technical portfolio.

---

# Core Strengths

- Security operations and endpoint triage.
- SIEM-style alert analysis and detection workflow documentation.
- Elastic and Wazuh detection operations.
- Splunk SOC workflows.
- Detection logic mapped to MITRE ATT&CK.
- Analyst playbooks and repeatable investigation workflows.
- Azure cloud security governance and control documentation.
- Vulnerability prioritization using EPSS, CISA KEV, NVD, and CVSS context.
- PowerShell and Python automation for security workflows.
- AI/tool-boundary security research.
- Bilingual Spanish/English technical communication.

---

# Technical Discussion Topics

- Alert triage and false-positive review.
- Suspicious PowerShell behavior and dual-use tooling.
- Failed logon burst detection and brute-force / password-spray logic.
- MITRE ATT&CK mapping for analyst communication.
- Analyst playbook design and evidence documentation.
- Elastic SIEM rule validation and alert evidence.
- Logstash pipeline configuration and troubleshooting.
- Wazuh decoder inspection and custom rule validation.
- KQL and Lucene investigation patterns.
- Apache log attack reconstruction.
- Splunk SPL triage, lookup enrichment, iplocation, eventstats, and alert-candidate logic.
- Splunk ingestion validation, reports, dashboards, parsing repair, and field extraction.
- Linux auth log, Apache access log, and network-log analysis.
- Active Directory persistence validation from a defender perspective.
- Azure RBAC scope and least-privilege governance.
- Azure Key Vault recovery protections.
- Azure Policy tag governance.
- Backup policy documentation and recovery-readiness reasoning.
- NIST SP 800-53 control-family mapping.
- Python-based CVE prioritization.
- EPSS, CISA KEV, NVD, and CVSS-based remediation prioritization.
- AI/tool-boundary safety principles.
- Cybersecurity writing, security analysis, and risk communication.
- Bilingual Spanish/English technical communication in support and security operations contexts.

---

# Availability and Contact

Open to fully remote cybersecurity roles focused on SOC operations, SIEM analysis, vulnerability management, information security, cloud security governance, and GRC-adjacent security work.

Best-fit roles: SOC Analyst, Security Analyst, MDR Analyst, SIEM Analyst, Vulnerability Analyst, Information Security Analyst, Cloud Security Analyst.

- LinkedIn: https://www.linkedin.com/in/gabriel-marquez-cyber/
- Email: gabriel.marquez.cyber@gmail.com
- GitHub: https://github.com/gabrielmarquezcyber

---

# Links

- LinkedIn: [linkedin.com/in/gabriel-marquez-cyber](https://www.linkedin.com/in/gabriel-marquez-cyber)
- Elastic SIEM Detection Engineering: [github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization](https://github.com/gabrielmarquezcyber/elastic-siem-detection-vuln-prioritization)
- Azure Cloud Security Governance: [github.com/gabrielmarquezcyber/azure-cloud-security-governance](https://github.com/gabrielmarquezcyber/azure-cloud-security-governance)
- Elastic and Wazuh Detection Operations Workbook: [github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook](https://github.com/gabrielmarquezcyber/elastic-wazuh-detection-operations-workbook)
- SOC Analyst Splunk Operations Workbook: [github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook](https://github.com/gabrielmarquezcyber/soc-analyst-splunk-operations-workbook)
- Active Directory Persistence Field Notes: [github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes](https://github.com/gabrielmarquezcyber/ad-persistence-defender-field-notes)
- Empire Breacher: [github.com/gabrielmarquezcyber/empire-breacher](https://github.com/gabrielmarquezcyber/empire-breacher)
- Cybersecurity Writing Portfolio: [github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio](https://github.com/gabrielmarquezcyber/cybersecurity-writing-portfolio)
