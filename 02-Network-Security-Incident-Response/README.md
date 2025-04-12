# NIST CSF Incident Response Analysis

## Project Overview
This project demonstrates the application of the NIST Cybersecurity Framework (CSF) to analyze and respond to a network security incident. Following a DDoS attack that compromised a multimedia company's internal network, I created a comprehensive incident response report using the five core functions of the NIST CSF: Identify, Protect, Detect, Respond, and Recover.

## Scenario Background
A multimedia company offering web design, graphic design, and social media marketing services experienced a DDoS attack that disrupted their network operations for two hours. The attack consisted of a flood of ICMP packets through an unconfigured firewall, preventing normal internal network traffic from accessing network resources.

## Incident Details
- **Attack Vector**: Flood of ICMP pings through an unconfigured firewall
- **Attack Type**: Distributed Denial of Service (DDoS)
- **Duration of Impact**: 2 hours
- **Affected Systems**: Internal network services

## Initial Response Actions
The incident management team implemented immediate measures:
- Blocked incoming ICMP packets
- Took non-critical network services offline
- Restored critical network services

## Technical Remediation
Following investigation, the network security team implemented:
- New firewall rules to limit incoming ICMP packet rates
- Source IP address verification to check for spoofed addresses
- Network monitoring software to detect abnormal traffic patterns
- IDS/IPS system to filter suspicious ICMP traffic

## NIST CSF Analysis
My incident response report analyzes this security event through the lens of the NIST CSF's five core functions:

### 1. Identify
Assessment of security risks through auditing internal networks, systems, devices, and access privileges to identify security gaps that contributed to the incident.

### 2. Protect
Recommendations for implementing policies, procedures, training, and tools to mitigate similar cybersecurity threats in the future.

### 3. Detect
Analysis of monitoring capabilities and suggestions for improving detection speed and efficiency for similar incidents.

### 4. Respond
Evaluation of the containment, neutralization, and analysis procedures used during the incident, with recommendations for improvement.

### 5. Recover
Assessment of the recovery process for affected systems and recommendations for improving restoration procedures.

## Skills Demonstrated
- Application of the NIST Cybersecurity Framework to a real-world incident
- Network security analysis
- DDoS attack remediation techniques
- Security control implementation
- Technical documentation and reporting
- Strategic security planning

## Tools and Methodologies Used
- NIST Cybersecurity Framework
- Network security analysis techniques
- Incident response procedures


*The **NIST_CSF_Reference_Guide.pdf** file used in this incident response analysis is available in the [reference-documents](./reference-documents) folder.*

This project showcases my ability to analyze security incidents using industry-standard frameworks and develop comprehensive response strategies that address both immediate technical needs and long-term security improvements.