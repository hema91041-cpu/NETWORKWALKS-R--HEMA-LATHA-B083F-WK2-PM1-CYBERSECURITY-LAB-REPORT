# NETWORKWALKS-HEMA-B083-WK2-PM1-CYBERSECURITY-LAB-REPORT

## 📌 Project Overview
This repository contains evidence and the final report for **Week 2 – Penetration Testing Module (PM1 & PM5)** under the NetworkWalks Cybersecurity Internship Program.  
The tasks focused on **Footprinting (Kali Linux tools)** and **Network Scanning (Zenmap)** against the permitted lab target.

---

## 🎯 Objectives
- Gather domain registration details (WHOIS).
- Detect web technologies (WhatWeb).
- Resolve DNS records (Nslookup, DNSRecon).
- Identify firewall presence (WAFW00F).
- Collect HTTP headers (Curl).
- Discover live hosts in subnet (Zenmap Ping Scan).
- Collect IP/MAC addresses.
- Generate and save network topology PDF.

---

## 🛠️ Tools & Commands
- **WHOIS** → `whois networkwalks.com`  
- **WhatWeb** → `whatweb networkwalks.com`  
- **Nslookup** → `nslookup networkwalks.com`  
- **Curl** → `curl -I https://networkwalks.com`  
- **WAFW00F** → `wafw00f networkwalks.com`  
- **DNSRecon** → `dnsrecon -d networkwalks.com`  
- **Zenmap Ping Scan** → `nmap -sn 10.42.27.0/24`

---

## 📂 Repository Structure
   Module1_Elective/ 
   
   curl.txt
   dnsrecon.txt
   nslookup.txt
   waf.txt
   whatweb.txt
   whois.txt

   Module1_Essential/
Zenmap_PingScan.txt
Topology.pdf

Report/
W2-PM-FINAL-Report.docx
W2-PM-FINAL-Report.pdf


---

## 📸 Evidence
Screenshots for 8 tasks are included in the final report:
- WHOIS, WhatWeb, Nslookup, Curl, WAFW00F, DNSRecon
- Zenmap Ping Scan, Zenmap Topology

---

## ✅ Results
- Domain registration details collected.  
- Web technologies fingerprinted.  
- DNS records enumerated.  
- Firewall presence detected.  
- HTTP headers analyzed.  
- Live hosts discovered in subnet `10.42.27.0/24`.  
- IP/MAC addresses documented.  
- Network topology PDF generated.

---

## ⚠️ Disclaimer
This work is strictly for **educational purposes** under the NetworkWalks Internship Program.  
All reconnaissance and scanning activities were performed against a **permitted lab target**.  
No unauthorized access was attempted.

---
