Here's a professional README that is suitable for GitHub, internships, project reviews, and viva presentations.

# Hybrid Cloud SOC Lab using Wazuh SIEM and AWS

## Overview

This project demonstrates the implementation of a Hybrid Cloud Security Operations Center (SOC) environment using Wazuh SIEM, AWS EC2, Ubuntu Linux, and VirtualBox. The objective of this project is to simulate how modern security teams monitor, detect, and analyze security events across cloud and on-premise environments.

A centralized Wazuh SIEM server was deployed on an Ubuntu Virtual Machine, while an AWS EC2 instance was used as a cloud endpoint. The project focuses on log collection, threat detection, security monitoring, and incident visibility through a centralized dashboard.

---

## Project Objectives

* Deploy and configure a Security Information and Event Management (SIEM) platform.
* Simulate a hybrid cloud monitoring environment.
* Monitor security events from cloud infrastructure.
* Analyze logs and detect suspicious activities.
* Gain hands-on experience with SOC operations and threat monitoring.
* Understand centralized security visibility and event correlation.

---

## Architecture

```text
                    AWS EC2 Instance
                 (Cloud Endpoint Server)
                           │
                           │
                    Wazuh Agent
                           │
                           ▼
        ┌────────────────────────────────┐
        │      Wazuh SIEM Server         │
        │      Ubuntu Virtual Machine    │
        │                                │
        │  • Wazuh Manager               │
        │  • Wazuh Dashboard             │
        │  • Wazuh Indexer               │
        └────────────────────────────────┘
                           │
                           ▼
                 SOC Analyst Dashboard
                   (Web Interface)
```

---

## Technologies Used

| Technology          | Purpose                             |
| ------------------- | ----------------------------------- |
| Wazuh               | SIEM Platform                       |
| Ubuntu Linux        | Server Operating System             |
| AWS EC2             | Cloud Endpoint                      |
| VirtualBox          | Virtualization Platform             |
| SSH                 | Secure Remote Access                |
| Nmap                | Network Scanning & Security Testing |
| Linux Commands      | System Administration               |
| HTML/CSS/JavaScript | Custom SOC Frontend                 |

---

## Key Features

* Centralized log collection and analysis
* Cloud endpoint monitoring
* Security event visualization
* Threat detection and alerting
* Real-time dashboard monitoring
* Hybrid cloud SOC architecture
* AWS integration
* Security event investigation

---

## Project Workflow

```text
Cloud Activity on EC2
          │
          ▼
Wazuh Agent Collects Logs
          │
          ▼
Logs Forwarded to Wazuh Manager
          │
          ▼
Threat Analysis and Rule Matching
          │
          ▼
Alert Generation
          │
          ▼
Dashboard Visualization
          │
          ▼
SOC Analyst Investigation
```

---

## Implementation Steps

### Phase 1 – Wazuh SIEM Deployment

* Installed Ubuntu Server on VirtualBox.
* Installed Wazuh Manager.
* Configured Wazuh Dashboard.
* Configured networking and dashboard access.
* Verified service availability.

### Phase 2 – Cloud Environment Setup

* Created AWS EC2 Ubuntu instance.
* Configured security groups.
* Established SSH connectivity.
* Prepared endpoint for monitoring.

### Phase 3 – Security Monitoring

* Connected monitored endpoint.
* Generated system activity and logs.
* Observed alerts and events through the Wazuh Dashboard.
* Performed security event analysis.

### Phase 4 – Frontend Development

* Designed a custom SOC dashboard interface.
* Created a modern analyst-focused monitoring interface.
* Integrated project architecture visualization.

---

## Security Events Monitored

* Authentication events
* Failed login attempts
* SSH activity
* Network activity
* System logs
* Endpoint activity
* Security alerts

## Learning Outcomes

Through this project, I gained practical experience in:

* Security Operations Center (SOC) concepts
* SIEM deployment and configuration
* Linux administration
* Cloud security monitoring
* AWS infrastructure management
* Log analysis and event monitoring
* Threat detection workflows
* Security monitoring architecture

---

## Future Enhancements

* SOAR integration using Shuffle
* Incident management with TheHive
* Automated response workflows
* Email and webhook alerting
* Threat intelligence integration
* Advanced attack simulations
* Multi-agent monitoring environment

---

## Conclusion

This project successfully demonstrates a Hybrid Cloud SOC environment where security events from cloud infrastructure can be monitored and analyzed through a centralized SIEM platform. It provides practical exposure to real-world SOC workflows, cloud monitoring, log management, and threat detection techniques commonly used in cybersecurity operations.



## Author

**Ruchir Vyas**

Cybersecurity | Cloud Security | SOC Operations | SIEM Monitoring


 
