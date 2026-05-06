# 🍯 Honeypot Deployment and Attack Monitoring

## 📌 Overview
This project demonstrates the deployment of a honeypot to simulate and monitor malicious activities in a controlled lab environment. The honeypot captures attacker behavior such as login attempts, credential usage, and command execution.

---

## 🎯 Objective
- Understand real-world attack patterns  
- Analyze attacker behavior on exposed services  
- Capture and monitor unauthorized access attempts  

---

## 🧱 Lab Setup

- **Attacker Machine:** Parrot Security OS  
- **Target Machine:** Ubuntu Server  
- **Honeypot Tool:** Cowrie  

Both systems were connected using an internal (host-only) network to ensure a secure and isolated environment.

---

## ⚙️ Methodology

The project was carried out in the following phases:

1. **Reconnaissance** – Identifying live hosts  
2. **Scanning** – Detecting open ports and services  
3. **Enumeration** – Gathering service details  
4. **Exploitation** – Simulating brute-force attacks  
5. **Post-Exploitation** – Monitoring attacker activity  

---

## 🛠️ Implementation

### 🔍 Reconnaissance
- Performed ARP scan to identify active hosts

### 📡 Scanning
- Used Nmap to detect open ports and services

### 🧠 Enumeration
- Interacted with services to identify potential entry points

### 💥 Exploitation
- Simulated SSH brute-force attack using Hydra

### 🍯 Honeypot Deployment
- Deployed Cowrie SSH honeypot on Ubuntu Server

### 📊 Monitoring
- Captured:
  - Login attempts  
  - Username/password combinations  
  - Attacker commands  

---

## 📊 Key Findings

- Common usernames like **root** were frequently targeted  
- Weak passwords such as **123456** were used  
- Attackers executed commands like:
  - `ls`
  - `whoami`

---

## 🛡️ Recommendations

### Immediate Fixes
- Remove or disable vulnerable services  
- Patch outdated services  

### Long-Term Measures
- Implement firewall rules  
- Deploy IDS/IPS  
- Conduct regular vulnerability assessments  

---

## 📚 Key Learnings

- Hands-on experience in honeypot deployment  
- Understanding attacker behavior  
- Log monitoring and analysis  
- Practical exposure to cybersecurity concepts  

---

## 📸 Screenshots

*(Add your screenshots in a separate folder and link here)*

---

## 📄 Report

Full detailed report available in the repository.

---

## 🚀 Tools Used

- Cowrie (SSH Honeypot)
- Nmap
- Hydra
- arp-scan

---

## 👨‍💻 Author

**Chirag B S**
