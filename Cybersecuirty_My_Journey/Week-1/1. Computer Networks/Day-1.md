# 🛡️ Cybersecurity Journey – Day 1: Networking Fundamentals

## 🧠 What is a Computer Network?

A computer network is a system that connects multiple devices (computers, servers, routers, etc.) to share information and resources efficiently. It includes:

- **Physical connections** – cables, switches, routers
- **Logical connections** – IP addressing, routing, protocols

---

## 🌐 Types of Computer Networks (Based on Size)

| Type     | Description                                                                   |
| -------- | ----------------------------------------------------------------------------- |
| **PAN**  | Personal Area Network – short range (e.g., Bluetooth devices, USB, NFC, ANT+) |
| **LAN**  | Local Area Network – within a building (e.g., home, office)                   |
| **WLAN** | Wireless LAN – LAN using wireless tech like Wi-Fi                             |
| **CAN**  | Campus Area Network – connects LANs within a campus                           |
| **MAN**  | Metropolitan Area Network – spans a city                                      |
| **WAN**  | Wide Area Network – covers large geographical areas (e.g., the internet)      |

---

### Ethernet

- Ethernet is the tradational technolgy for connecting devices in a wired local area network (LAN)

---

## 🧱 Network Architecture

- Network architecture generally refers to the design of a computer network or communications network. It simply describes the allocation task between all of the computers in the network. It is simply a way in which all network devices and services are organized and managed to connect clients like laptops, tablets, servers, etc., and also how tasks are allocated to computers. It is defined as the physical and logical design of software, hardware, protocols, and media of data transmission.

- **Peer-to-Peer (P2P)** – each node is equal and communicates directly
- **Client-Server** – centralized server provides services to clients

---

## 🔁 Network Protocols

- A network protocol is a set of rules that govern data communication between different devices in the network. It determines what is being communicated, how it is being communicated, and when it is being communicated. It permits connected devices to communicate with each other, irrespective of internal and structural differences.

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

| Layer             | Purpose                      | Example Protocols           |
| ----------------- | ---------------------------- | --------------------------- |
| Application       | End-user services            | HTTP, FTP, SNMP, SMTP, POP3 |
| Transport         | End-to-end connection        | TCP, UDP                    |
| Internet          | Logical addressing & routing | IP, ARP                     |
| Network Interface | Physical transmission        | Ethernet, Token Ring        |

---

## 🧾 MAC Address – Media Access Control

A MAC address is the **unique physical identifier** for a device's **Network Interface Card (NIC)**.

### 🔍 Key Characteristics:

| Property           | Description                             |
| ------------------ | --------------------------------------- |
| **Layer (OSI)**    | Layer 2 – Data Link Layer               |
| **Layer (TCP/IP)** | Network Interface Layer                 |
| **Size**           | 6 bytes (48 bits)                       |
| **Format**         | Hexadecimal (e.g., `00:21:70:6F:06:F2`) |

### 📦 Structure

- **First 3 Bytes (24 bits)** → Assigned by **IEEE**  
  Called the **Organizationally Unique Identifier (OUI)**  
  Identifies the manufacturer (e.g., Dell, HP)

- **Last 3 Bytes (24 bits)** → Assigned by **manufacturer**  
  Usually sequential to ensure uniqueness per device

> 🔢 `2^24` = **~16.7 million** unique device addresses per manufacturer

### 🧪 Examples

00:21:70:6F:06:F2
00-21-70-6F-06-F2

---

## 🧾 IP vs MAC Address

| IP Address                                          | MAC Address                                                       |
| --------------------------------------------------- | ----------------------------------------------------------------- |
| Network (OSI Layer 3) Addresses                     | Data Link (OSI Layer 2) Addresses                                 |
| Logical Addresses                                   | Physical Addresses                                                |
| Assigned in Operating System                        | Physically burned on NIC                                          |
| Allows network-to-network communication via routers | Allows internetwork communication via hubs, switches, and routers |
| WAN communication                                   | Local LAN communication                                           |

---

## 🔁 Duplex Communication Modes

Network communication will occur in either full or half duplex mode:

- **Half Duplex:** Can send and receive data, but not at the same time.
- **Full Duplex:** Can send and receive data simultaneously.

---

## 🛰️ Transmission Types

- Transmission mode means transferring data between two devices. It is also known as a communication mode. Buses and networks are designed to allow communication to occur between individual devices that are interconnected. There are three types of transmission modes:
- **Unicast** – One-to-one
- **Multicast** – One-to-many (selected)
- **Broadcast** – One-to-all (within a LAN)

---

## 🔌 Network Topologies

- Network topology is the way devices are connected in a network. It defines how these components are connected and how data transfer between the network. Understanding the different types of network topologies can help in choosing the right design for a specific network.

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
🔜 Day 2 – Networking Devices


