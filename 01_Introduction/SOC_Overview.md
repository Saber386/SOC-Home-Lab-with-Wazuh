# Security Operations Center (SOC)

## Overview

A Security Operations Center (SOC) is a centralized team responsible for continuously monitoring, detecting, investigating, and responding to cybersecurity threats across an organization's infrastructure.

The primary goal of a SOC is to identify malicious activities as early as possible, minimize the impact of security incidents, and improve the overall security posture of the organization.

A modern SOC combines skilled analysts, standardized processes, and security technologies such as SIEM, EDR, SOAR, IDS/IPS, and Threat Intelligence Platforms.

---

# Primary Objectives

* Monitor security events continuously.
* Detect suspicious or malicious activities.
* Investigate security alerts.
* Respond to security incidents.
* Reduce organizational cyber risk.
* Improve visibility across enterprise infrastructure.

---

# Core Responsibilities

A SOC is responsible for:

* Security Monitoring
* Alert Triage
* Threat Detection
* Log Analysis
* Incident Investigation
* Incident Response
* Threat Hunting
* Vulnerability Monitoring
* Security Reporting

---

# SOC Workflow

```text
Logs Generated
        │
        ▼
Log Collection
        │
        ▼
SIEM
        │
        ▼
Detection Rules
        │
        ▼
Alert Generated
        │
        ▼
SOC Analyst
        │
        ▼
Investigation
        │
        ▼
Incident Response
        │
        ▼
Remediation
```

---

# SOC Roles

### Tier 1 Analyst

* Monitor dashboards
* Validate alerts
* Filter false positives
* Escalate incidents

### Tier 2 Analyst

* Investigate alerts
* Perform log analysis
* Identify root cause
* Contain incidents

### Tier 3 Analyst

* Advanced investigation
* Malware analysis
* Threat hunting
* Detection engineering

---

# Common Technologies

| Technology          | Purpose                                    |
| ------------------- | ------------------------------------------ |
| SIEM                | Log collection and correlation             |
| EDR                 | Endpoint monitoring                        |
| XDR                 | Extended detection across multiple sources |
| SOAR                | Security automation                        |
| IDS/IPS             | Network threat detection                   |
| Threat Intelligence | IOC enrichment                             |

---

# Skills Required

* Networking
* Windows
* Linux
* Log Analysis
* SIEM
* MITRE ATT&CK
* Incident Response
* Python / PowerShell
* Basic Scripting

---

# Key Takeaways

* Everything in a SOC revolves around **logs**.
* SIEM is the heart of a SOC.
* Detection rules convert logs into alerts.
* Analysts investigate alerts before declaring incidents.
* Not every alert is an attack; false positives are common.
* Documentation is an essential part of every investigation.

---

# In This Repository

This repository focuses on building a practical SOC Home Lab using:

* Wazuh
* Sysmon
* Windows Event Logs
* Kali Linux
* Ubuntu Server
* Detection Rules
* Attack Simulations
* Incident Investigation
* MITRE ATT&CK Mapping

The objective is to understand how enterprise Security Operations Centers detect, investigate, and respond to cyber threats through hands-on implementation rather than theory alone.


