# 🛡️ Incident Report Analysis: ICMP Flood DDoS Attack

This project analyzes a real-world DDoS attack scenario against a multimedia company and outlines the response and recovery plan using the NIST Cybersecurity Framework (CSF).

---

## 📘 Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses.

Recently, the organization experienced a **Distributed Denial of Service (DDoS)** attack, which compromised the internal network for two hours. The attack involved a flood of **ICMP packets**, preventing normal network traffic from accessing resources.

### 📌 Incident Overview

- **Attack vector:** ICMP Flood
- **Impact:** Network services were unresponsive for 2 hours
- **Initial response:** Blocked incoming ICMP packets, shut down non-critical services, restored critical services
- **Vulnerability exploited:** Unconfigured firewall

---

## 🧰 Mitigations Implemented

- 🔒 New firewall rule to limit incoming ICMP packet rates  
- 🧠 Source IP verification to detect spoofed IPs  
- 📊 Network monitoring software for abnormal traffic detection  
- 🛡️ IDS/IPS system to filter ICMP traffic based on suspicious characteristics  

---

## 🧭 NIST Cybersecurity Framework (CSF) Alignment

### 🧾 Summary

The company faced a security event when all network services stopped responding. The cybersecurity team identified the cause as a **DDoS attack**, which flooded the network with incoming ICMP packets. To resolve the issue, the team blocked the attack and shut down non-critical services, allowing **critical services** to be restored.

---

### 🔍 Identify

A malicious actor or group launched an **ICMP flood attack** on the company, affecting the internal network. As a result, all critical network resources had to be **secured and restored** to normal operation.

---

### 🛡️ Protect

The cybersecurity team:
- Added a **new firewall rule** to control the rate of incoming ICMP packets  
- Implemented an **IDS/IPS system** to filter suspicious ICMP traffic  

---

### 👁️ Detect

To improve detection capabilities, the team:
- Configured **source IP address verification** on the firewall to detect spoofed IPs  
- Deployed **network monitoring software** to flag unusual traffic patterns  

---

### 🚨 Respond

In future security events, the cybersecurity team plans to:
- **Isolate affected systems** to reduce spread  
- Prioritize **critical systems recovery**  
- **Analyze logs** for suspicious activity  
- **Report incidents** to management and, if necessary, legal authorities  

---

### 🔄 Recover

To recover from similar incidents:
- **Restore essential services first**  
- **Block external ICMP traffic** during recovery  
- Gradually bring **non-critical systems** back online once the threat is mitigated  


---

## 📎 Disclaimer

This scenario is a simulated training exercise From Google Cybersecurity Certificate used for educational purposes in cybersecurity response planning and documentation.
