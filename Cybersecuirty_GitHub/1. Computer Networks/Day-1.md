# 🛡️ Cybersecurity Journey – Day 1: Networking Fundamentals

## 🧠 What is a Computer Network?

A computer network is a system that connects multiple devices (computers, servers, routers, etc.) to share information and resources efficiently. It includes:

- **Physical connections** – cables, switches, routers
- **Logical connections** – IP addressing, routing, protocols

---

## 🌐 Types of Computer Networks (Based on Size)

| Type     | Description                                                              |
| -------- | ------------------------------------------------------------------------ |
| **PAN**  | Personal Area Network – short range (e.g., Bluetooth devices)            |
| **LAN**  | Local Area Network – within a building (e.g., home, office)              |
| **WLAN** | Wireless LAN – LAN using wireless tech like Wi-Fi                        |
| **CAN**  | Campus Area Network – connects LANs within a campus                      |
| **MAN**  | Metropolitan Area Network – spans a city                                 |
| **WAN**  | Wide Area Network – covers large geographical areas (e.g., the internet) |

---

## 🧱 Network Architecture

- **Peer-to-Peer (P2P)** – each node is equal and communicates directly
- **Client-Server** – centralized server provides services to clients

---

## 🔁 Network Protocols

- **Physical Protocols** – define electrical/physical specifications (e.g., Ethernet)
- **Logical Protocols** – define logical communication and data formats (e.g., TCP/IP)

---

## 📊 OSI Model (Reference Model by ISO, 1977)

The OSI model has 7 layers and is used to conceptualize how data travels across a network.

| Layer           | Data Unit | Description                               |
| --------------- | --------- | ----------------------------------------- |
| 7. Application  | Data      | User interface, application services      |
| 6. Presentation | Data      | Data translation, encryption, compression |
| 5. Session      | Data      | Session control, dialogs                  |
| 4. Transport    | Segment   | Reliable delivery (TCP), error recovery   |
| 3. Network      | Packet    | Routing, logical addressing (IP)          |
| 2. Data Link    | Frame     | MAC addressing, error detection           |
| 1. Physical     | Bit       | Transmission of raw bits                  |

- The **upper layers (5–7)** = Host layer
- The **lower layers (1–4)** = Media layer

> Note: OSI is a reference model. Actual implementations use the TCP/IP model.

---

## 🌐 TCP/IP Model (Real-world implementation)

| Layer             | Purpose                      | Example Protocols |
| ----------------- | ---------------------------- | ----------------- |
| Application       | End-user services            | HTTP, FTP, DNS    |
| Transport         | End-to-end connection        | TCP, UDP          |
| Internet          | Logical addressing & routing | IP, ICMP          |
| Network Interface | Physical transmission        | Ethernet, ARP     |

---

## 🧾 IP vs MAC Address

| Property | IP Address               | MAC Address                       |
| -------- | ------------------------ | --------------------------------- |
| Type     | Logical (Software-level) | Physical (Hardware-level)         |
| Scope    | Changes across networks  | Permanent (NIC-specific)          |
| Use Case | Routing over networks    | Device identification within LANs |

---

## 🔁 Duplex Communication Modes

- **Simplex** – one-way (e.g., keyboard to CPU)
- **Half-Duplex** – both ways, but one at a time (e.g., walkie-talkie)
- **Full-Duplex** – simultaneous two-way communication (e.g., phone)

---

## 🛰️ Transmission Types

- **Unicast** – One-to-one
- **Multicast** – One-to-many (selected)
- **Broadcast** – One-to-all (within a LAN)

---

## 🔌 Network Topologies

### Wired Topologies:

| Type     | Description                              |
| -------- | ---------------------------------------- |
| **Bus**  | Single backbone, terminators at each end |
| **Ring** | Data travels in a loop                   |
| **Star** | Central hub connects all nodes           |
| **Mesh** | Every node connected to every other      |

### Wireless Topologies:

| Type               | Description                                     |
| ------------------ | ----------------------------------------------- |
| **Ad-hoc**         | Devices connect directly without infrastructure |
| **Infrastructure** | Devices connect via Access Point                |
| **Wireless Mesh**  | Nodes dynamically connect and reconfigure       |

---

## 🔑 Key Takeaways for Interviews

- Understand the layered approach of OSI & TCP/IP — this will help in diagnosing and securing network traffic.
- Be clear on MAC vs IP — important for network access control.
- Topology questions are common — especially Star, Mesh, and Ad-hoc scenarios.
- Familiarity with protocols (physical/logical) is essential for moving into Application Security and Ethical Hacking.

---

📅 **Progress Tracker**
✅ Day 1 Complete – Fundamentals of Networking  
🔜 Day 2 – Deeper into TCP/IP Stack, Ports, and Protocols
