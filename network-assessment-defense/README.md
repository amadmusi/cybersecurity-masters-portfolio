# Network Assessment & Defense — Security Monitoring and Incident Response


## Project Overview

This graduate cybersecurity project focused on evaluating and strengthening the network security 
posture of a simulated software development organization, North Star Software Developers.

The project involved analyzing network traffic, evaluating firewall and network segmentation strategies, 
working with intrusion detection and prevention concepts, monitoring security logs and alerts, and 
developing incident response and mitigation procedures.

## Key Areas

- Network traffic analysis
- Packet capture and inspection
- Firewall configuration and traffic filtering
- Network segmentation
- Intrusion Detection and Prevention Systems (IDS/IPS)
- Security monitoring and log analysis
- Security alert investigation
- Detection of suspicious network activity
- Incident response procedures
- Security mitigation and remediation

## Tools & Technologies

- Wireshark
- tcpdump
- Snort
- Linux
- Firewalls
- Intrusion Detection and Prevention Systems (IDS/IPS)
- Network monitoring and logging


## Scenario

North Star Software Developers is a simulated organization
used to evaluate common network security challenges.

The environment required an assessment of network traffic,
security controls, firewall protections, and intrusion
detection capabilities.

The project focused on identifying suspicious activity,
evaluating existing defenses, and developing procedures
for detecting, responding to, and mitigating security
incidents.

## What I Did

- Captured and analyzed network traffic to identify
  normal and potentially suspicious activity.

- Used packet capture and traffic analysis tools to
  examine network communications and behavior.

- Reviewed Snort alerts and logs to identify suspicious
  activity, including repeated login attempts.

- Evaluated firewall rules and traffic filtering to
  determine how network access should be controlled.

- Assessed network segmentation strategies to limit
  unnecessary communication between systems.

- Evaluated IDS/IPS placement and monitoring strategies
  for detecting potentially malicious activity.

- Developed procedures for responding to security alerts
  and escalating potential incidents.

- Documented mitigation and incident response
  recommendations to strengthen the network's defenses.

## Skills Demonstrated

- Network traffic analysis
- Security monitoring
- Log and alert analysis
- Network security
- IDS/IPS monitoring
- Firewall security
- Network segmentation
- Threat and anomaly identification
- Incident response
- Security documentation
- Mitigation planning

## Project Takeaways

This project strengthened my ability to analyze network
activity from a defensive security perspective and connect
technical findings to incident response decisions.

Working with packet captures, security alerts, firewall
controls, and IDS/IPS concepts provided practical experience
in identifying suspicious activity and determining how
security controls can reduce network risk.

The project also reinforced the importance of clear
documentation when communicating security findings,
response procedures, and mitigation recommendations.

## Lab Evidence & Technical Demonstrations

The following screenshots document selected hands-on exercises completed as part of the network assessment and defense project. The labs were performed in isolated cybersecurity training environments and demonstrate practical use of network analysis, vulnerability assessment, intrusion detection, security monitoring, and incident response tools.

### Network Traffic Analysis with Wireshark
Used Wireshark to inspect captured network traffic and follow TCP streams. Analysis demonstrated how unencrypted application protocols can expose sensitive information, including FTP authentication activity, transferred files, and email content.

### Network Discovery and Port Scanning
Used ARP Scan, Nmap, and Zenmap to discover systems on a simulated LAN, identify active hosts, enumerate open ports and services, and perform operating-system detection.

### Vulnerability Assessment
Used Greenbone Security Assistant to configure vulnerability scans, review discovered services and vulnerabilities, and examine CVE information associated with identified security weaknesses.

### Intrusion Detection and Packet Monitoring
Used tcpdump and Snort to capture network traffic and analyze IDS alerts. Snort rules and alert logs were examined to identify suspicious activity including repeated FTP authentication attempts and other potentially malicious traffic.

### Security Logging and Time Synchronization
Configured and reviewed Snort, RSYSLOG, and NTP components in a Linux environment to support centralized security logging, accurate event records, and network monitoring.

### Security Testing and Service Analysis
Used controlled security-testing tools in an isolated lab environment to evaluate exposed network services and authentication weaknesses. Activities included service enumeration and analysis using Nmap, Zenmap, Hydra, Metasploit, and Armitage.

> All activities shown were performed in authorized academic lab environments using simulated systems provided for cybersecurity training.


## Selected Lab Evidence

### Wireshark — Plaintext FTP Traffic Analysis
![Wireshark FTP TCP Stream](screenshots/Picture%201.png)

Followed an FTP TCP stream in Wireshark and examined plaintext authentication and file-transfer activity, demonstrating the security risk of transmitting sensitive information over unencrypted protocols.

### Wireshark — Email Traffic Analysis
![Wireshark Email TCP Stream](screenshots/Picture%202.png)

Inspected captured email traffic by following a TCP stream and demonstrated how message content can be reconstructed when application traffic is transmitted without adequate encryption.

### Snort — Intrusion Detection and Alert Analysis
![Snort IDS Alerts](screenshots/Picture%209.png)

Reviewed Snort IDS alerts generated from suspicious network activity, including repeated FTP authentication attempts, to identify and analyze potentially malicious traffic.

### Nmap and Zenmap — Host and Service Enumeration
![Nmap and Zenmap Enumeration](screenshots/Picture%2011.png)

Performed network reconnaissance using Nmap and Zenmap to identify active systems, enumerate open ports and services, and assess the exposed network attack surface.

### Greenbone — Vulnerability Assessment
![Greenbone Vulnerability Assessment](screenshots/Picture%2013.png)

Used Greenbone Security Assistant to review discovered services and vulnerability scan results and examine CVE information associated with identified weaknesses.

Performed host discovery on a simulated LAN using ARP Scan to identify active systems and their associated network addresses before conducting deeper security assessment.

### Snort, RSYSLOG, and Security Logging
![Security Logging Configuration](screenshots/Picture%2023.png)

Configured Snort logging and RSYSLOG components in Linux to support security-event collection, alert logging, and centralized monitoring.

### Service and Authentication Security Testing
![Security Testing](screenshots/Picture%2023.png)

Performed controlled service and authentication testing within an isolated lab environment to evaluate exposed services and identify weaknesses that could enable unauthorized access.
