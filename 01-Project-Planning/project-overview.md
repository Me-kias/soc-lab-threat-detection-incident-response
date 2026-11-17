# SOC Lab – Threat Detection & Incident Response

## 1. Project Overview

This project involves building a practical Security Operations Centre (SOC) home lab to develop hands-on skills in cybersecurity monitoring, threat detection, log analysis and incident response.

The lab will simulate security events in a controlled environment, collect system logs, detect suspicious activities and investigate security alerts using a Security Information and Event Management (SIEM) platform.

## 2. Project Objectives

- Build a virtual SOC environment.
- Configure centralised security monitoring using Wazuh SIEM.
- Collect and analyse Windows Security Event Logs.
- Configure Sysmon for detailed endpoint monitoring.
- Simulate common cybersecurity threats in a controlled lab.
- Investigate security alerts and identify suspicious activity.
- Develop Python scripts for security log analysis.
- Document investigations and incident response procedures.

## 3. Planned Technologies

| Technology | Purpose |
|---|---|
| Oracle VirtualBox | Virtualisation |
| Ubuntu Server | SOC server operating system |
| Wazuh SIEM | Security monitoring and threat detection |
| Windows 10/11 | Monitored endpoint |
| Sysmon | Detailed Windows system monitoring |
| Kali Linux | Security testing workstation |
| Python | Security log analysis and automation |
| Git and GitHub | Version control and project documentation |
| Wireshark | Network traffic analysis |
| MITRE ATT&CK | Threat behaviour classification |

## 4. Planned Detection Scenarios

1. Brute-force login attempts.
2. Successful login following multiple failed attempts.
3. Unexpected user account creation.
4. Privilege escalation through administrator group membership.
5. Suspicious PowerShell execution.

## 5. Expected Deliverables

- A functional virtual SOC lab environment.
- Centralised security log collection and monitoring.
- Tested security detection scenarios.
- Security investigation reports.
- Python security-analysis scripts.
- Technical documentation and screenshots.
- A documented GitHub portfolio project.

## 6. Project Status

**Current stage:** Infrastructure setup.

**Completed so far:**
- Installed Oracle VirtualBox on the Windows 11 host.
- Installed Ubuntu Server in a VirtualBox virtual machine.
- Confirmed that Ubuntu Server is running.

**Next steps:**
1. Verify Ubuntu Server version and system resources.
2. Update Ubuntu packages.
3. Install and configure Wazuh.
4. Set up the Windows monitored endpoint.
5. Configure Sysmon and the Wazuh agent.

## 7. Learning Objectives

Throughout this project, I aim to develop practical knowledge of:

- Security Operations Centre (SOC) fundamentals.
- SIEM architecture and alert investigation.
- Windows and Linux system administration.
- Log collection and analysis.
- Threat detection and incident response.
- Networking and security monitoring.
- Python scripting and automation.
- MITRE ATT&CK techniques.

---

*Note: This document describes the project plan and current progress. Planned tasks will only be marked as completed after implementation and testing.*
