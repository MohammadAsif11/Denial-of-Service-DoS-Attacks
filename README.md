# 🔐 Denial of Service (DoS) Attacks – Practical Overview

## 👤 Author
**Mohammad Asif**  
Cybersecurity | Ethical Hacking | Hands-on Security Labs  

---

## 📌 Repository Overview
This repository contains **four Denial of Service (DoS) attack practicals** performed in a **controlled virtual lab environment**.  
The objective of these practicals is to understand how different DoS techniques affect **system availability, network performance, and web services**.

All attacks were conducted using **private IP addresses** on intentionally vulnerable systems for **educational purposes only**.

---

## 🧪 Practicals Included

### 1️⃣ ICMP Ping Flood Attack
An **ICMP-based DoS attack** where continuous ping requests are sent to a target system.  
This overwhelms the network and CPU resources, causing the system to become slow or unresponsive.

---

### 2️⃣ TCP SYN Flood Attack (hping3)
A **transport-layer DoS attack** that sends a large number of TCP SYN packets without completing the TCP handshake.  
This creates multiple half-open connections and exhausts the target system’s resources.

---

### 3️⃣ TCP SYN Flood Attack (Metasploit Framework)
This practical uses **Metasploit auxiliary DoS modules** to perform a TCP SYN Flood attack.  
It demonstrates how automated tools can be used to disrupt network services and system availability.

---

### 4️⃣ Slowloris Attack on DVWA (Metasploitable 2)
An **application-layer (Layer 7) DoS attack** targeting the DVWA web application.  
Slowloris keeps multiple HTTP connections half-open, exhausting the web server’s connection pool and making the website unstable or inaccessible.

---

## 🎯 Key Learning Outcomes
- Understanding different **types of DoS attacks**
- Observing **resource exhaustion behavior**
- Difference between **network-layer, transport-layer, and application-layer attacks**
- Importance of **defensive security mechanisms**

---

## ⚠️ Ethical Disclaimer
> These practicals were conducted **only in a controlled lab environment** using private IP addresses and intentionally vulnerable systems.  
> This repository is strictly for **learning and educational purposes**.

---

## 📫 Connect with Me
- **GitHub:** https://github.com/MohammadAsif11  
- **LinkedIn:** https://www.linkedin.com/in/mohammad-asif-585a4b264/

---
