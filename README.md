# 🕵️ Packet Sniffing Project (Scapy + Python)

This project demonstrates the practical use of a **packet sniffer** built using Python and the Scapy library. The goal is to capture, analyze, and extract valuable information from real-time network packets for the purpose of learning and understanding network behavior.

> ⚠️ This project is strictly for **educational and authorized research** purposes. Unauthorized sniffing is illegal and unethical.

---

## 📌 Project Summary

Packet sniffers are tools that monitor and capture packets flowing through a network. This project focuses on:
- Capturing network packets
- Filtering by protocol layers (TCP, UDP, HTTP)
- Extracting and analyzing specific fields like URLs and credentials
- Applying real-time monitoring to understand network traffic flow

---

## 📄 Documentation

[📥 Download the Full Report (PDF)](./Packet_Sniffing_Project.pdf)

---

## 🛠 Tools & Technologies

| Tool         | Description                         |
|--------------|-------------------------------------|
| Python 3     | Programming language used           |
| Scapy        | Python-based network packet library |
| Kali Linux   | Operating system for penetration testing |
| PyCharm      | Python IDE used for development     |

---

## 🔬 Features & Functionality

### ✅ Step-by-Step Procedure

#### 1. Sniffing Packets
- Uses `sniff()` from Scapy to capture packets in real time.

#### 2. Filtering Layers
- Filters data based on layers like `TCP`, `UDP`, or custom filters.

#### 3. Extracting Data
- Retrieves information from different layers such as source/destination IPs, ports, and payloads.

#### 4. Analyzing Sensitive Fields
- Attempts to extract useful information such as passwords (if found in raw payloads).

#### 5. Extracting URLs
- Specifically captures visited URLs in HTTP requests by analyzing payload data.

---

## ⚙️ How to Run

```bash
sudo python3 packet_sniffer.py
