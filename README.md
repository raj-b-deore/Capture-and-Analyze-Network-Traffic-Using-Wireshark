# 📡 Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

---

## 🧰 Tools Used
- Wireshark (Free Network Packet Analyzer)

---

## ⚙️ Procedure

1. Installed Wireshark along with Npcap.
2. Selected the active Wi-Fi network interface.
3. Started live packet capture.
4. Generated traffic by:
   - Browsing websites
   - Running `ping google.com`
5. Captured packets for 60 seconds.
6. Applied protocol filters:
   - DNS
   - TCP
   - HTTP
7. Exported capture file as `.pcap`.

---

## 🔍 Protocols Identified

| Protocol | Description |
|----------|-------------|
| DNS | Resolves domain names into IP addresses |
| TCP | Provides reliable data transmission |
| HTTP | Used for web communication |
| ICMP | Used for ping requests |
| ARP | Maps IP address to MAC address |

---

## 📊 Packet Analysis Summary

- DNS Packets: Observed during domain name resolution.
- TCP Packets: Observed during communication between client and server.
- HTTP Packets: Observed while accessing websites.
- ICMP Packets: Observed during execution of ping command.
- ARP Packets: Observed for IP to MAC address mapping.

---

## 📸 Screenshots

### Active Interface Selection
<img width="1915" height="1141" alt="Image" src="https://github.com/user-attachments/assets/50d7a1a1-8ee6-41c8-958a-d60a594eeba1" />

### DNS Protocol Filter
<img width="1919" height="1142" alt="Image" src="https://github.com/user-attachments/assets/86334c2e-c9a7-4d9a-b214-a6098077e809" />


### TCP Protocol Filter
<img width="1919" height="1139" alt="Image" src="https://github.com/user-attachments/assets/05823334-9dfa-4f7d-9dbf-1f9b74f63f70" />

### HTTP Protocol Filter
<img width="1919" height="1138" alt="Image" src="https://github.com/user-attachments/assets/1466a586-12b8-4448-8b27-cb94b9046516" />

### Packet Details
<img width="1919" height="1095" alt="Image" src="https://github.com/user-attachments/assets/b1bc1a06-4498-465d-b5b7-573229f4b154" />

### Command Prompt
<img width="1474" height="497" alt="Image" src="https://github.com/user-attachments/assets/9de7d529-3ee4-429e-b9b7-2e470d47f025" />

---

## 💾 Output File

Captured packet file:

[Download network_capture.pcap](network_capture.pcap)

---

## ✅ Outcome

Successfully captured and analyzed live network traffic using Wireshark.  
Identified multiple network protocols such as DNS, TCP, HTTP, ICMP, and ARP, gaining practical knowledge of packet-level network communication.

---

