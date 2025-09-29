# 🛡️ Cyber Security Internship - Task 5

## 🎯 Task: Capture and Analyze Network Traffic Using Wireshark

This repository contains the submission for **Task 5** of the Cyber Security Internship. The objective was to use **Wireshark** to capture live network traffic and analyze at least 3 protocols such as **DNS**, **TCP**, and **TLS**.

---

## 🧰 Tools & Environment

- **Operating System:** Kali Linux (in VirtualBox)
- **Packet Capture Tool:** Wireshark
- **Date of Capture:** 29 September 2025

---

## 📁 Files Included

| File Name | Description |
|-----------|-------------|
| `All traffic.png` | Screenshot showing a general overview of captured packets |
| `DNS filter.png` | View filtered to show only DNS traffic |
| `TCP filter.png` | View filtered to show only TCP packets |
| `Expanded packet view.png` | A selected packet with headers and hex data expanded |
| `task5_capture_yourname.pcapng` | Wireshark packet capture file (replace with actual file) |
| `report.md` | Short report summarizing protocol analysis |

---

## 🖼️ Screenshots Preview

### 🔹 1. All Traffic View
![All Traffic](./All%20traffic.png)

---

### 🔹 2. DNS Filtered View
![DNS Filter](./DNS%20filter.png)

---

### 🔹 3. TCP Filtered View
![TCP Filter](./TCP%20filter.png)

---

### 🔹 4. Expanded Packet View
![Expanded Packet View](./Expanded%20packet%20view.png)

---

## 🔍 Protocols Analyzed

### ✅ DNS
- **Purpose:** Resolves domain names like `google.com` to IP addresses
- **Captured:** DNS query and response visible in filtered view

### ✅ TCP
- **Purpose:** Ensures reliable delivery using SYN, ACK handshakes
- **Captured:** TCP Keep-Alive, SYN/ACK packets from web traffic

### ✅ TLSv1.3
- **Purpose:** Encrypts HTTP traffic using HTTPS
- **Captured:** TLS handshake packets visible when accessing `github.com`

---

## 📄 Summary

Wireshark was successfully used to capture and analyze live network traffic on Kali Linux. By visiting websites and using `ping`, several protocols were identified, filtered, and inspected in detail. Screenshots and a `.pcapng` capture file are provided as proof of analysis and learning.

---

## ✍️ Author

**Tarun M**  
Cyber Security Internship Candidate  
**Task 5 Submission for Elevate Labs**
