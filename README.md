# Network Forensics Investigations

## Executive Summary

This project contains structured forensic investigations of suspicious network traffic designed to simulate enterprise incident response investigations.

Each investigation reconstructs attacker behavior through packet-level traffic analysis and identifies indicators of compromise across multiple advanced attack scenarios including DNS tunneling, command-and-control communication, beaconing, lateral movement, suspicious SMB activity, and ARP poisoning.

The project demonstrates practical network-centric incident investigation methodologies used by security analysts to identify malicious communication patterns and assess organizational exposure.

---

## Objectives

- Perform packet-level forensic analysis
- Identify malicious network indicators
- Reconstruct attacker timelines
- Document indicators of compromise
- Assess business impact
- Recommend remediation strategies

---

## Investigation Scenarios

- DNS tunneling detection
- Beacon interval analysis
- ARP spoofing investigation
- SMB lateral movement analysis
- Suspicious TLS communication analysis
- Command-and-control traffic reconstruction

---

## Investigation Workflow

### Packet Inspection

Raw packet captures are analyzed for:

- Abnormal protocol behavior
- Suspicious communication intervals
- Data exfiltration indicators
- Payload irregularities

---

### IOC Identification

Indicators include:

- Randomized domain generation
- Large TXT record responses
- Repetitive outbound beacon traffic
- Unauthorized internal lateral communication

---

### Timeline Reconstruction

Traffic flows are sequenced to reconstruct attacker behavior.

---

### Analyst Assessment

Security impact and confidence ratings are assigned.

---

## Technologies Used

- Wireshark
- Tshark
- PCAP Analysis
- DNS Protocol Inspection
- Network Traffic Correlation

---

## Key Findings

Analysis identified persistent high-frequency DNS communication to randomized external infrastructure strongly consistent with DNS-based command-and-control behavior.

Traffic reconstruction suggested stealthy beaconing intervals designed to evade threshold-based alerting systems.

---

## Severity Classification

- Critical Investigations: 3
- High-Risk Findings: 6
- Medium Suspicion Cases: 5

---

## Deliverables

- Packet investigation reports
- IOC extraction documentation
- Attack timelines
- Analyst conclusions
- Security remediation recommendations
