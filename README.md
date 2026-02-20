# cybersecurity-task-1
Performed local network reconnaissance using Nmap to identify active hosts and open ports. Conducted a TCP SYN scan, analyzed exposed services, assessed potential security risks, and documented mitigation strategies as part of a cybersecurity internship task.
# 🔍 Local Network Port Scanning using Nmap

## 📌 Project Overview
This project demonstrates basic network reconnaissance by scanning a local network to identify active hosts and open ports. The task was completed as part of a Cyber Security Internship to understand network exposure and potential security risks.

---

## 🎯 Objective
To perform a TCP SYN scan on the local IP range and analyze open ports to evaluate possible security vulnerabilities.

---

## 🛠 Tools Used
- **Nmap** – For performing TCP SYN scan
- **Wireshark (Optional)** – For packet capture and traffic analysis
- Command Prompt / Terminal
- Git & GitHub for documentation

---

## 🌐 IP Range Scanned
Example: `192.168.1.0/24`

---

## 🚀 Command Used

```bash
nmap -sS 192.168.1.0/24 -oN nmap_scan.txt -oX nmap_scan.xml
