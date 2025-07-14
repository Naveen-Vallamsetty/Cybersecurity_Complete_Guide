# Networking Hardware and Network Cabling

## Network Interface Card (NIC)

- A NIC is a hardware component that connects a computer to a network.
- It operates at **OSI Layer 1 (Physical Layer)** and **Layer 2 (Data Link Layer)**.
- Responsible for converting data into a format suitable for transmission over a network medium (electrical or optical signals).
- Provides a unique **MAC address** for each network-enabled device.

---

## Hubs

- A hub is a basic networking device used at **OSI Layer 1 (Physical Layer)**.
- **Legacy equipment**, largely replaced by switches.
- **Broadcasts data to all ports**, causing **network collisions**.
- Called a **multi-port repeater**: data goes in one port and is **repeated (broadcasted)** out every other port.
- **Drawbacks**:
  - Cannot filter data or detect destination.
  - Increases traffic and collision rates.

---

## Switches

- Operate at **OSI Layer 2 (Data Link Layer)**.
- Use **MAC addresses** to filter and forward traffic only to the correct port.
- Uses a **Content Addressable Memory (CAM)** table.
- **Application-Specific Integrated Circuit (ASIC)** helps store the MAC addresses for efficient data forwarding.
- Understands **Source and Destination MAC addresses**.

---

## Wireless Access Point (WAP)

- Extends wired network into wireless (creates WLAN).
- Not a router, works similarly to a switch but for wireless devices.
- Operates at **OSI Layer 2 (Data Link Layer)**.

---

## Wireless Range Extender

- Acts as a **wireless repeater**.
- Extends wireless signal by **rebroadcasting the signal**.
- Commonly used brand: NETGEAR.

---

## Routers

- Connect different networks together.
- Operate at **OSI Layer 3 (Network Layer)**.
- Use **IP addresses** and **routing protocols**.
- Break up **broadcast domains**.

---

## Modem (Modulator/Demodulator)

- Converts **analog signals to digital** and vice versa.
- Enables internet access over telephone lines.
- Performs both modulation (sending) and demodulation (receiving) of signals.

---

## SOHO Devices (Small Office/Home Office)

- All-in-one devices: combine router, switch, WAP, firewall, DHCP server, NAT, file server, etc.

---

## Media Converters

- **Layer 1 (Physical Layer)** devices.
- Convert signal formats (e.g., Ethernet to Fiber Optic).

---

## Firewalls

- Security devices used to block unauthorized access while permitting legitimate communication.
- Can be hardware (network-based) or software (host-based).
- **Filters data packets** to prevent malicious traffic.
- **Types**:
  - **1st Gen**: Packet filtering.
  - **2nd Gen**: Circuit-level (valid TCP sessions).
  - **3rd Gen**: Application Layer/NGFW.

---

## DHCP Server (Dynamic Host Configuration Protocol)

- Automatically assigns IP addresses to hosts.
- **DORA process**: Discover → Offer → Request → Acknowledge.

---

## VoIP Endpoints (Voice over IP)

- Enable voice communication over IP networks.
- Use **SIP (Session Initiation Protocol)**.
- Examples: IP phones, Cisco Jabber.

---

## Ports in Networking

- Hardware endpoints to connect with external devices
- Software-defined endpoints for communication.
- Examples:
  - **HTTP**: Port 80
  - **HTTPS**: Port 443

---

## Network Cabling

### Ethernet

- IEEE 802.3 standard for LAN communication.
- Uses **CSMA/CD** for wired and **CSMA/CA** for wireless communication.

### Ethernet Naming Convention

- **10Base-T**:
  - 10 Mbps speed
  - Baseband signaling
  - Twisted pair cabling

---

## Twisted Pair Cabling

- **4 twisted pairs**, typically terminated with an **RJ-45 connector**.
- **Why twisted?** To reduce **crosstalk** and **electromagnetic interference (EMI)**.

### Shielded vs Unshielded

- **UTP**: Unshielded Twisted Pair – More EMI
- **STP**: Shielded Twisted Pair – Better noise resistance

### Roles of Twists

- Reduce Crosstalk
- Increase Signal Integrity
- Support Higher Speeds

### Cable Categories and Specs

| Category | Type       | Speed   | Distance |
| -------- | ---------- | ------- | -------- |
| Cat 5e   | 1000Base-T | 1 Gbps  | 100 m    |
| Cat 6    | 1000Base-T | 1 Gbps  | 100 m    |
| Cat 6    | 10GBase-T  | 10 Gbps | 55 m     |
| Cat 6a   | 10GBase-T  | 10 Gbps | 100 m    |
| Cat 7    | 10GBase-T  | 10 Gbps | 100 m    |

## Basic Data Unit Conversions

- 1 bit = Smallest unit of data (either 0 or 1)
- 1 byte = 8 bits
- 1 kilobyte (KB) = 1024 bytes
- 1 megabyte (MB) = 1024 kilobytes
- 1 gigabyte (GB) = 1024 megabytes
- 1 terabyte (TB) = 1024 gigabytes
- 1 petabyte (PB) = 1024 terabytes

### Wiring Standards

- **TIA/EIA 568A & 568B** define pin arrangements for RJ-45.
- **Straight-through cable**: Connects unlike devices (PC to switch).
- **Crossover cable**: Connects like devices (PC to PC).

---

## Fiber Optic Cables

- **Uses light (photons)** instead of electricity.
- **Immune to EMI** and supports long-distance, high-speed transmission.

### Types

| Type | Core Size  | Range        |
| ---- | ---------- | ------------ |
| MMF  | 50–62.5 µm | Up to 2 km   |
| SMF  | 8–10 µm    | Up to 200 km |

### Fiber Connectors

- **LC (Lucent Connector)** – Small form, MMF & SMF
- **SC (Subscriber Connector)** – MMF & SMF
- **ST (Straight Tip)** – Legacy MMF
- **MTRJ (Mechanical Transfer Registered Jack)** – Compact MMF

---

## Coaxial Cable

- Used in traditional TV and older Ethernet.
- **F-Connector**: Screw-on connector for cable modems.
- **RG (Radio Guide) Types**:
  - RG-6: Modern cable modems
  - RG-59: CCTV
  - RG-8/58: Old Ethernet (10Base5, 10Base2)

---

## Plenum-Rated Cable

- Plenum-rated cables are designed for use in the plenum spaces of buildings.
- Fire-retardant and emit less smoke/toxic gases during fires.
- Compliant with fire codes and building safety standards.

---

📅 **Progress Tracker**  
✅ Day 2 Complete – Networking Devices & Network Cabling  
🔜 Day 3 Preview – OSI Model & TCP/IP Deep Dive
