<h1>📡 Packet Capture & Traffic Analysis Lab</h1>

<h2>📌 Overview</h2>
This project focuses on **packet capture and traffic analysis** using **Wireshark** to inspect various network protocols and detect potential security threats. The lab explores **normal and malicious network traffic**, including ICMP, SSH, FTP/SFTP, WLAN encryption, and deauthentication attacks.

<h2>🛠 Tools & Technologies Used</h2>

- **Wireshark** – Network traffic analysis & deep packet inspection  
- **aircrack-ng** – Wireless network attack simulation  
- **SecureLabs Test Network** – Simulated network environment for controlled packet capture  

<h2>🔍 Key Findings & Analysis</h2>

| Network Traffic | Description | Analysis & Observations |
|----------------|-------------|-------------------------|
| **ICMP (Ping) Packets** | Standard network diagnostic messages. | Identified ICMP payload and source/destination details. |
| **SSH Traffic** | Secure communication channel. | Verified encryption and MAC selections. |
| **FTP vs. SFTP Traffic** | File transfer protocols. | Observed plain-text FTP vs. encrypted SFTP authentication. |
| **WLAN Encryption** | Wi-Fi security handshake. | Captured WPA2 4-way handshake, analyzed SSID & channels. |
| **Deauthentication Attack** | Malicious disconnect attack. | Used `aireplay-ng` to force disconnects and analyzed packets. |

<h2>🚀 Report & Documentation</h2>

📄 **[Download Full Report (PDF)](https://github.com/user-attachments/files/18663150/Performing.Packet.Capture.and.Traffic.Analysis.4e.-.Marc.Corona.pdf)**  
📂 **Captured Traffic & Screenshots**:
- `icmp_traffic.pcap` – ICMP packet analysis  
- `ssh_traffic.pcap` – SSH encrypted session capture  
- `ftp_vs_sftp.pcap` – Comparison of FTP and SFTP authentication  
- `wlan_handshake.pcap` – Captured WPA2 4-way handshake  
- `deauth_attack.pcap` – Deauthentication attack traffic  

<h2>✅ Key Takeaways & Security Implications</h2>

🔹 **Plain-text protocols (FTP) expose credentials and should be replaced with secure alternatives (SFTP).**  
🔹 **Wireless networks are vulnerable to deauthentication attacks without strong security policies.**  
🔹 **Packet inspection is essential for detecting anomalies and identifying security risks.**  


---
