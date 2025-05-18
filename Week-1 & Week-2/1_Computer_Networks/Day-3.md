# 🧠 Day 3 – OSI Model In-Depth

---

## 📚 OSI Layers Overview

The OSI Model has **7 layers**, each handling specific functions for network communication.

---

### 1. Application Layer (Layer 7)

- Provides user interface and directly interacts with end-user applications.
- **Protocols:**
  - Email: **IMAP4**, **POP3**, **SMTP**
  - Web Browsing: **HTTP**, **HTTPS**
  - Remote Access: **SSH**, **Telnet**

---

### 2. Presentation Layer (Layer 6)

- Responsible for:
  - Character code conversion
  - Data compression and encryption/decryption
- **Examples:**
  - Web Browser: **HTML** converted to **ASCII** format
- **Common File Formats:**
  - **Web Browser Files:** HTML, XML, JavaScript
  - **Graphics Files:** JPEG, GIF, PNG
  - **Audio/Video Files:** MPEG, MP3
  - **Encryption Protocols:** TLS, SSL
  - **Text/Data:** ASCII, EBCDIC

---

### 3. Session Layer (Layer 5)

- Manages sessions (start, maintain, end) between network devices or applications.

- **Different Methods of Communication:**
  - **Simplex:** One-way communication
  - **Half Duplex:** Two-way but one direction at a time
  - **Full Duplex:** Two-way simultaneous communication

---

### 4. Transport Layer (Layer 4)

- Ensures data delivery is **error-free** and **in sequence**.
- Segments and reassembles data.

- **Transport Protocols:**

  - **TCP (Transmission Control Protocol):** Connection-oriented
  - **UDP (User Datagram Protocol):** Connectionless

- **Data Flow Control Measures:**
  - **Buffering:** Temporary storage of data
  - **Windowing:** Determines the window size of data sent without acknowledgment

---

### 5. Network Layer (Layer 3)

- Routing Layer — handles logical addressing and path selection.

- **Key Functions:**

  - Assigns Source and Destination IP addresses to packets.

- **Types of Packets:**

  - **Data Packets:** IPv4, IPv6
  - **Route-Update Packets:** RIP, OSPF, EIGRP

- **Layer 3 Devices and Protocols:**
  - Routers and Multilayer Switches
  - IP Addressing (IPv4, IPv6)
  - ICMP (Internet Control Message Protocol) — used in **ping**

---

### 6. Data Link Layer (Layer 2)

- Switching Layer — ensures messages are delivered correctly within a LAN using MAC addresses.

- **Key Concepts:**

  - Frames are created and managed.
  - **Sublayers:**
    - **LLC (Logical Link Control):** Error and flow control
    - **MAC (Media Access Control):** Hardware addressing (48-bit MAC address burned into NIC)

- **Technologies:**
  - Ethernet, Token Ring
  - **Access Methods:**
    - **CSMA/CD:** Collision Detection (Wired Ethernet)
    - **CSMA/CA:** Collision Avoidance (Wireless networks)

---

### 7. Physical Layer (Layer 1)

- Deals with the physical connection between devices.
- Sends and receives raw bits (0s and 1s).

- **Signal Encoding Mediums:**

  - Electrical: Copper cables
  - Radio: Wireless signals
  - Light: Fiber optics

- **Key Components:**
  - Network Cabling, Jacks, Patch panels
  - Physical Network Topologies (Star, Mesh, Ring, Bus, etc.)
  - Ethernet Standards (IEEE 802.3)
  - Devices: Hubs, Media Converters, Modems

---

## 🔄 OSI Model Encapsulation and De-encapsulation

- Encapsulation: Adding headers/trailers at each layer before sending.
- De-encapsulation: Removing headers/trailers at each layer when receiving.

---

📅 Progress Tracker  
✅ Day 3 Complete – OSI Model In-Depth  
🔜 Day 4 – Planning a Network & TCP/IP Model In-Depth  
