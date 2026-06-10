# OT/SCADA Security Monitoring Lab using OpenPLC, SCADA, Modbus TCP and Wazuh SIEM on Google Cloud Platform.

## Overview

This project demonstrates the deployment and monitoring of an Operational Technology (OT) / SCADA environment using OpenPLC and Wazuh SIEM on Google Cloud Platform (GCP).

The lab simulates an industrial control environment and implements security monitoring capabilities including:

* Vulnerability Detection
* File Integrity Monitoring (FIM)
* Endpoint Monitoring
* Security Event Collection
* OpenPLC Runtime Monitoring

---

## Architecture

Google Cloud VM

├── OpenPLC SCADA

├── Modbus TCP Services

└── Wazuh Agent

↓

Wazuh Server & Dashboard

↓

Security Monitoring & Alerting

---

## Technologies Used

- OpenPLC (Industrial PLC Simulation)
- SCADA Monitoring Environment
- Modbus TCP Protocol
- Wazuh SIEM
- Ubuntu Linux
- Google Cloud Platform (GCP)
- File Integrity Monitoring (FIM)
- Vulnerability Detection
  
---

## Implemented Security Controls

### 1. Vulnerability Detection

Wazuh Vulnerability Detector was configured to identify vulnerable packages and software components running on the OpenPLC host.

Features:

* CVE Identification
* Severity Classification
* Vulnerable Package Inventory
* Risk Visibility Dashboard

---

### 2. File Integrity Monitoring (FIM)

Wazuh Syscheck was configured to monitor critical directories and files.

Demonstrated Events:

* File Added Detection
* File Modified Detection
* Integrity Checksum Validation

Example monitored file:

/home/zaidz8852/OpenPLC_v3/test.txt

Generated Events:

* Rule 554 (File Added)
* Rule 550 (File Modified)

---

### 3. Endpoint Monitoring

The OpenPLC host was onboarded as a monitored endpoint in Wazuh.

Collected telemetry includes:

* System Information
* Package Inventory
* Network Information
* Process Information
* Security Events

---

## Screenshots

### Vulnerability Dashboard

![Vulnerability Dashboard](screenshots/WhatsApp%20Image%202026-06-09%20at%203.17.40%20PM.jpeg)

### SCADA Monitoring Dashboard

![Endpoint Monitoring](screenshots/WhatsApp%20Image%202026-06-09%20at%203.17.40%20PM%20\(1\).jpeg)

### File Integrity Monitoring Events

![FIM Events](screenshots/WhatsApp%20Image%202026-06-09%20at%203.17.40%20PM%20\(2\).jpeg)

### OpenPLC Runtime

![OpenPLC Runtime](screenshots/WhatsApp%20Image%202026-06-09%20at%203.17.40%20PM%20\(3\).jpeg)

---

## Key Achievements

* Built a functional OT/SCADA security lab.
* Integrated OpenPLC with Wazuh SIEM.
* Detected file additions and modifications in real time.
* Monitored vulnerabilities affecting the SCADA host.
* Implemented endpoint visibility and security monitoring.
* Deployed and managed the environment on Google Cloud Platform.

---

## Future Improvements

* Network Intrusion Detection
* ICS Protocol Monitoring
* MITRE ATT&CK Mapping
* Automated Incident Response
* Threat Hunting Dashboards

---

## Author

Zeyad Alharbi

GitHub:
https://github.com/Zeyad0x
