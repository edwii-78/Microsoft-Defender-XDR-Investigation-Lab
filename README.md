# Microsoft Defender XDR Investigation Lab

## Overview

This repository documents a series of enterprise-style SOC investigations performed using Microsoft Defender XDR and Microsoft Defender for Endpoint.

Rather than focusing on detection engineering, these projects emphasize how Security Operations Center (SOC) analysts investigate, correlate, assess, and respond to security incidents using Microsoft's Extended Detection and Response (XDR) platform.

The investigations simulate real-world enterprise workflows including endpoint incident analysis, automated investigation, threat intelligence operationalization, proactive threat hunting, cross-domain incident correlation, and live endpoint response.

---

## Objectives

- Investigate endpoint security incidents using Microsoft Defender XDR.
- Analyze alerts, evidence, and device telemetry.
- Reconstruct attack timelines using Process Tree and Device Timeline.
- Perform IOC extraction and MITRE ATT&CK mapping.
- Assess security impact and containment decisions.
- Utilize Defender's automated investigation and response capabilities.
- Perform proactive threat hunting using Advanced Hunting.
- Correlate endpoint, identity, email, and cloud telemetry into unified XDR incidents.
- Demonstrate enterprise live response and forensic investigation workflows.

---

# Project Roadmap

| Project | Focus | Primary Skill |
|---------|-------|---------------|
| Project 01 | Endpoint Incident Investigation | SOC Investigation Methodology |
| Project 02 | Automated Investigation & Attack Disruption | Automated Remediation & Response |
| Project 03 | Threat Intelligence & IOC Management | Indicator Operationalization |
| Project 04 | Advanced Hunting & Proactive Threat Hunting | Threat Hunting |
| Project 05 | Enterprise XDR Incident Correlation | Cross-Domain Investigation |
| Project 06 | Live Response & Enterprise Forensics | Endpoint Response & DFIR |

---

# Investigation Workflow

```
Alert
    │
    ▼
Incident
    │
    ▼
Evidence Collection
    │
    ▼
Device Timeline
    │
    ▼
Process Tree
    │
    ▼
Investigation Graph
    │
    ▼
IOC Analysis
    │
    ▼
MITRE ATT&CK Mapping
    │
    ▼
Risk Assessment
    │
    ▼
Containment Decision
    │
    ▼
Incident Closure
```

---

# Technologies

- Microsoft Defender XDR
- Microsoft Defender for Endpoint
- Microsoft Defender Antivirus
- Windows 11
- Active Directory
- Microsoft Entra ID (later projects)
- Microsoft Defender for Office 365 (later projects)
- Microsoft Defender for Cloud Apps (later projects)
- Kusto Query Language (KQL)
- MITRE ATT&CK Framework

---

# Repository Structure

```
Microsoft-Defender-XDR-Investigation-Lab

│
├── Project-01-Endpoint-Incident-Investigation
├── Project-02-Automated-Investigation-and-Attack-Disruption
├── Project-03-Threat-Intelligence-and-IOC-Management
├── Project-04-Advanced-Hunting-and-Proactive-Threat-Hunting
├── Project-05-Enterprise-XDR-Incident-Correlation
└── Project-06-Live-Response-and-Enterprise-Forensics
```

---

# Skills Demonstrated

- Endpoint Incident Investigation
- Incident Triage
- Alert Correlation
- Evidence Analysis
- IOC Management
- Threat Intelligence
- MITRE ATT&CK Mapping
- Threat Hunting
- Endpoint Containment
- Live Response
- Enterprise Incident Response

---

# Related Projects

- Wazuh SOC Detection Engineering Lab
- Splunk SOC Detection Engineering Lab
- Microsoft Sentinel SIEM and SOAR Lab
