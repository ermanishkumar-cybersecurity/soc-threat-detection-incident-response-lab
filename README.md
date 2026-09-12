# SOC Threat Detection & Incident Response Lab

## 📌 Project Overview

This project demonstrates a hands-on Security Operations Center (SOC) lab focused on Windows threat detection, security monitoring, and incident response.

The lab uses Sysmon and Windows Event Logs as telemetry sources and Splunk for log collection, analysis, detection, and investigation.

The project focuses on identifying suspicious activities, investigating security alerts, building attack timelines, identifying indicators of compromise (IOCs), and mapping observed behaviors to the MITRE ATT&CK framework.

## 🛠️ Technologies & Tools

- **Splunk**
- **Sysmon**
- **Windows Event Logs**
- **PowerShell**
- **MITRE ATT&CK**

## 🎯 Objectives

- Collect and analyze Windows security events.
- Monitor endpoint activity using Sysmon telemetry.
- Develop detection queries for suspicious activities.
- Investigate security alerts using multiple log sources.
- Identify indicators of compromise (IOCs).
- Build attack timelines during incident investigation.
- Map detected behaviors to MITRE ATT&CK techniques.
- Document incident findings and recommended remediation actions.

## 🔍 Threat Detection

The lab focuses on detecting and investigating activities such as:

- Brute-force authentication attempts
- Suspicious PowerShell activity
- Privilege escalation
- Abnormal process execution

Detection queries are used in Splunk to search and analyze relevant Windows Event Logs and Sysmon telemetry.

## 🕵️ Incident Investigation

The investigation process includes:

1. Reviewing security alerts in Splunk.
2. Analyzing relevant Windows Event Logs.
3. Examining Sysmon telemetry.
4. Correlating events from different sources.
5. Identifying suspicious processes and activities.
6. Building an attack timeline.
7. Identifying indicators of compromise (IOCs).
8. Determining affected systems.
9. Assessing incident severity.
10. Documenting findings and recommended remediation.

## 🧩 MITRE ATT&CK Mapping

Detected attack behaviors are mapped to relevant techniques in the **MITRE ATT&CK** framework.

The mapping helps understand:

- Initial attack behavior
- Execution techniques
- Privilege escalation activity
- Credential-related activity
- Process execution
- Other observed attacker behaviors

## 🚨 Incident Findings

For each investigated security event, the lab documents:

- **Alert / Detection**
- **Observed Activity**
- **Affected System**
- **Indicators of Compromise (IOCs)**
- **Attack Timeline**
- **Severity**
- **MITRE ATT&CK Mapping**
- **Recommended Remediation**

## 📊 Splunk Investigation

Splunk is used to:

- Search Windows Event Logs.
- Analyze Sysmon events.
- Filter suspicious activity.
- Correlate related events.
- Investigate authentication activity.
- Analyze process execution.
- Identify suspicious PowerShell activity.
- Support incident timeline reconstruction.

## 🔒 Project Scope & Ethics

This project was performed in a controlled lab environment for educational and defensive security purposes.

- Testing was performed only on systems under authorized control.
- No unauthorized systems or real-world organizations were targeted.
- Attack simulations, where applicable, were conducted only within the controlled lab environment.

## 📚 Key Takeaways

- Developed practical experience with SOC monitoring and threat detection.
- Improved understanding of Windows security telemetry.
- Gained hands-on experience analyzing Sysmon and Windows Event Logs.
- Practiced security alert investigation using Splunk.
- Learned to correlate events and reconstruct attack timelines.
- Improved understanding of IOC identification and incident severity.
- Practiced mapping security behaviors to MITRE ATT&CK.
- Strengthened incident response and defensive security skills.
