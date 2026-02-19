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


### DNS Protocol Filter


### TCP Protocol Filter


### HTTP Protocol Filter


### Packet Details


---

## 💾 Output File

Captured packet file:

network_capture.pcap

---

## ✅ Outcome

Successfully captured and analyzed live network traffic using Wireshark.  
Identified multiple network protocols such as DNS, TCP, HTTP, ICMP, and ARP, gaining practical knowledge of packet-level network communication.

---

