# Day 4 - Cybersecurity Learning Journey 🚀

## Topic: Network Planning and TCP/IP Protocols

---

## 🔧 Network Planning Considerations

- Troubleshooting issues
- Scalability
- Reliability
- Security
- Data loss prevention
- Costly rework

### 🛠️ Network Lifecycle Phases

1. Plan
2. Design
3. Implement
4. Maintain
5. Tune (Continuous Improvement)

### ❓ Network Planning Questions

- Peer-to-peer or Client-server?
- Cabling type: UTP, STP, Fiber Optic, Wireless
- Centralized or distributed printing?
- Internal or external email system?
- Centralized data requirement?
- Security: Physical & Logical?

---

## 🧠 Network Design Process

- Convert plans to design
- Physical topology and layout
- Logical topology
- Define & document specifications

---

## 🧩 TCP/IP Model & Protocols

| Layer             | Protocols                                                                   |
| ----------------- | --------------------------------------------------------------------------- |
| Application       | FTP, TFTP, DNS, HTTP(S), TLS/SSL, SSH, POP3, IMAP4, NTP, Telnet, SMTP, SNMP |
| Transport         | TCP, UDP                                                                    |
| Internet          | IP, ICMP, ARP                                                               |
| Network Interface | Ethernet, Token Ring                                                        |

### 🛰️ CSMA/CD vs CSMA/CA

- Carrier Sense Multiple Access
- CSMA/CD: Collision Detection (Wired)
- CSMA/CA: Collision Avoidance (Wireless)

### 🧾 Token Ring

- Token passed between devices
- Only the holder can transmit
- Prevents collisions

---

## 🔄 Address Resolution Protocols

- **ARP**: IP → MAC (via `arp -a`)
- **RARP**: MAC → IP
- **ARP Cache**: Stores resolved addresses

---

## 🌐 IP & ICMP

- **IP**: Logical addressing & routing (no error recovery)
- **ICMP**: Error reporting (e.g., Ping)

### Common ICMP Messages

- Echo request/reply
- Destination unreachable
- Redirect
- Time exceeded
- Router advertisement (IPv6)

---

## 🔌 Ports, Protocols, and Services

- Total: 65,536 ports
  - 0–1023: Well-known
  - 1024–49151: Registered
  - 49152–65535: Dynamic

#### Examples:

- **IIS (Web Server)**: Port 80/443
- **DHCP**: Ports 67/68
- **DNS**: Port 53 (UDP)
- **NTP**: Port 123 (TCP)
- **SNMP**: Port 161 (TCP)
- **LDAP**: 389 (TCP), LDAPS: 636 (TCP/SSL)
- **SMB**: Port 445 (TCP)

---

## 🔁 TCP vs UDP

| Feature     | TCP                       | UDP             |
| ----------- | ------------------------- | --------------- |
| Connection  | Yes                       | No              |
| Reliability | High                      | Low             |
| Use Cases   | Web, Email, File Transfer | Streaming, VoIP |

**TCP Handshake:**  
`SYN → SYN/ACK → ACK`  
**Closing TCP Session:**  
`FIN, ACK → ACK → FIN, ACK → ACK`

---

## 📡 Remote Protocols

| Protocol | Port                    | Secure?         |
| -------- | ----------------------- | --------------- |
| Telnet   | 23                      | ❌ (Deprecated) |
| SSH      | 22                      | ✅              |
| RDP      | 3389                    | ✅              |
| FTP      | 20 (data), 21 (control) | ❌              |
| SFTP     | 22                      | ✅              |
| TFTP     | 69 (UDP)                | ❌ (Simple use) |

---

## ✉️ Email Protocols

| Protocol | Port | Use             |
| -------- | ---- | --------------- |
| SMTP     | 25   | Sending Mail    |
| POP3     | 110  | Retrieving Mail |
| IMAP     | 143  | Accessing Mail  |

---

## 🌍 Web Protocols

- **HTTP**: Port 80 (Plain text)
- **HTTPS**: Port 443 (Encrypted - SSL/TLS)

---

📅 Progress Tracker  
✅ Day 4 Complete – Planning a Network & TCP/IP Model  
🔜 Day 5 – IPv4 & IPv6, Subnetting & DNS Deep Dive
