What is an IP address?

What is a port number? Give 3 examples.

What is the difference between TCP and UDP?

What is a packet?

Why is HTTPS more secure than HTTP?

What is the difference between a private and public IP address?

What is a subnet mask?

What tools do you use for network analysis?

What is port scanning, and how is it useful in cybersecurity?

Explain what happens when you type www.google.com in a browser.

Absolutely, Naveen! 👨‍🏫
Here are clean, **interview-ready answers** for the 5 questions from **Lesson 1** — perfect to copy into your **GitHub README** under an `📄 Interview Questions` section.

---

## 📄 Interview Questions – Lesson 1: Internet & Packets

### 1. ❓**What is the Internet?**

**Answer:**
The Internet is a global network of interconnected networks that allows computers and devices to communicate with each other. It works using protocols like **TCP/IP** to send and receive data in the form of packets.

---

### 2. ❓**What is a Packet?**

**Answer:**
A packet is a small unit of data sent over a network. Each packet contains:

- **Source IP** (where it's from)
- **Destination IP** (where it’s going)
- **Payload** (actual data)
- **Header** (delivery information)

Packets are reassembled at the destination to form the original message.

---

### 3. ❓**What is the role of DNS?**

**Answer:**
DNS (Domain Name System) converts **human-readable domain names** (like `google.com`) into **IP addresses** (like `142.250.192.78`), which are required for computers to find and communicate with each other over the Internet.

---

### 4. ❓**Why do we use IP addresses?**

**Answer:**
An IP address is a unique identifier for each device on a network. It allows data to be routed accurately between devices over the Internet, just like a home address guides postal mail.

---

### 5. ❓**What command sends packets to test a connection?**

**Answer:**
The `ping` command is used to test network connectivity between your device and another host. It sends **ICMP (Internet Control Message Protocol)** packets and measures the response time.

---

Let me know when you’ve added them to GitHub — I can review the formatting if you'd like.
When ready, say **“Next lesson, Shifu!”** and we’ll begin Lesson 2: **IP Address – The Digital Address System** 🧠🌐

🧪 Interview Q&A
❓What is an IP address?
👉 It’s a unique address used to identify devices on a network.

❓What are the differences between public and private IPs?
👉 Private IPs are used within internal networks; public IPs are used to connect to the Internet.

❓What command is used to find IP in Linux/Windows?
👉 ipconfig (Windows), ifconfig or ip a (Linux)

🧪 Interview Questions
❓What is a port number?
👉 It's a numeric identifier for a specific service on a device (like HTTP or SSH).

❓Give 3 examples of common ports and what they’re used for.
👉 80: HTTP, 22: SSH, 443: HTTPS

❓Which tool is used for port scanning?
👉 Nmap

🧠 Interview Tip:
Q: What would you do if Nmap says "Host seems down"?
A: I would try -Pn to skip the ping step, because the host might be blocking ping probes.

🧠 Interview Mini-Quiz:
❓1. What is TCP?
✅ A reliable, connection-based protocol for accurate data transfer.

❓2. What is UDP used for?
✅ Fast, real-time communication where losing a few packets is okay.

❓3. Which is used by HTTP/HTTPS?
✅ TCP (for accurate, ordered delivery)

❓4. Is DNS TCP or UDP?
✅ Mostly UDP, but can use TCP for large transfers.
