<p align="center">
  <img src="https://img.icons8.com/fluency/120/network-card.png" width="120"/>
</p>

<h1 align="center">🛰️ CodeAlpha: Advanced Network Sniffer</h1>

<p align="center">
  <strong>Professional Real-Time Network Packet Analysis & Threat Detection Tool</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Packet%20Engine-Scapy-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/GUI-CustomTkinter-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-success?style=for-the-badge"/>
</p>

---

## 📌 Project Overview

**CodeAlpha Advanced Network Sniffer** is a professional-grade **Network Packet Monitoring and Threat Detection Tool** developed for **Task 1 – CodeAlpha Cyber Security Internship**.

The application provides:

- Real-time network packet capture  
- Protocol-level analysis  
- Deep packet inspection (DPI)  
- Security threat detection  
- Modern, command-center style GUI  

Designed with **performance, usability, and security visibility** in mind.

---

## 🚀 Key Features

### 📡 Real-Time Packet Capture
- Captures live traffic from selected network interfaces
- Supports:
  - TCP
  - UDP
  - ICMP

---

### 📊 Security Dashboard
- Live packet monitoring metrics
- Protocol distribution tracking
- Real-time **Safety Meter** indicating network risk level

---

### 🔬 Deep Packet Inspection (DPI)

#### ✅ Decoded Packet Analysis
- Human-readable IP Header data
- TTL analysis
- Protocol-level breakdown

#### 🧾 Raw Hex Payload Viewer
- Offset-based hex dump
- ASCII interpretation
- Professional forensic-style packet view

---

### 🛡️ Threat Detection Engine
- Detects suspicious port activity:
  - Unauthorized SSH attempts
  - RDP scanning attempts
- Flags potential plaintext credential exposure:
  - password
  - login
  - user fields
- OS fingerprint estimation using TTL patterns

---

### 🎨 Modern UI / UX
- Built using **CustomTkinter**
- Command-center style professional interface
- Dynamic Light / Dark mode switching
- Risk-based packet highlighting:
  - 🔴 High Risk
  - 🟠 Medium Risk

---

## 🛠️ Technical Stack

| Component | Technology |
|---|---|
| Language | Python 3.10+ |
| Packet Processing | Scapy |
| GUI Framework | CustomTkinter |
| Concurrency | Threading + Queue |
| Architecture | Modular Core + UI Separation |

---

## 📋 Prerequisites & Installation

### 🧩 1️⃣ Windows Users — Critical Driver

For packet capture on Windows, install **Npcap**:

👉 https://npcap.com/

⚠️ During Installation:
✅ Check **"Install Npcap in WinPcap API-compatible Mode"**

Then restart your:
- Terminal
- IDE

---

### 🐍 2️⃣ Install Python Dependencies

```bash
pip install scapy customtkinter
```

### 🚦 Usage

⚠️ Must run with Administrator / Root privileges
(Required for raw packet capture)

### Windows (PowerShell as Administrator)
```bash
python main.py
```

### 🐧 Linux
```bash
sudo python3 main.py
```

### 📁 Project Structure
```text
CodeAlpha_Network_Sniffer/
├── core/
│   ├── sniffer_engine.py     # Packet capture engine
│   └── parser.py             # DPI & threat detection logic
│
├── ui/
│   ├── main_window.py        # Packet viewer & inspector panel
│   └── dashboard.py          # Metrics dashboard & safety meter
│
├── main.py                   # Application entry point
└── README.md                 # Project documentation
```

## 🧠 Architecture Highlights

- Multi-threaded capture engine  
- Non-blocking UI updates using Queue system  

**Modular Separation:**
- Capture Engine  
- Analysis Engine  
- GUI Layer  

---

## ⚠️ Ethical Use Disclaimer

This tool is developed strictly for:

- ✅ Educational Purposes  
- ✅ Ethical Security Testing  
- ✅ Authorized Network Monitoring  

🚫 Unauthorized packet sniffing is **illegal and unethical**.  

The developer is not responsible for misuse.

---

## 👤 Author

**Mohsin Haider Sultan**  
Cyber Security Intern – CodeAlpha  

🧠 AI • 🛡️ Cybersecurity • 💻 Software Engineering  
🎓 BS Computer Science  

---

## 📜 Internship Details

- **Program:** CodeAlpha Cyber Security Internship  
- **Task:** Task 1 – Basic Network Sniffer  
- **Organization:** CodeAlpha  

---

## 📄 License

This project is provided for **educational and internship demonstration purposes**.

---

<p align="center">
  <strong>CodeAlpha Network Sniffer — Observe. Analyze. Secure.</strong>
</p>

