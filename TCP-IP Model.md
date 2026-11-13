# 🌐 TCP/IP Model – Understanding the 4 Layers

## 📖 Overview

The **TCP/IP Model (Transmission Control Protocol/Internet Protocol)** is a networking framework that explains how data travels between devices over a network and the internet.

It consists of four layers, each responsible for a specific networking function. These layers work together to ensure that data is properly transmitted, routed, delivered, and received by the destination device.

---

## 🧩 The Four Layers of the TCP/IP Model

| Layer | Main Function | Examples of Protocols |
|---|---|---|
| 4. Application | Provides network services to applications. | HTTP, HTTPS, DNS, FTP, DHCP, SMTP |
| 3. Transport | Handles communication between devices and applications. | TCP, UDP |
| 2. Internet | Handles logical addressing and packet routing. | IPv4, IPv6, ICMP |
| 1. Network Access | Handles physical network transmission and local delivery. | Ethernet, Wi-Fi, ARP |

---

## 1️⃣ Network Access Layer

### Overview

The **Network Access Layer** is responsible for transmitting data across the local network. It handles how devices connect to the network through physical or wireless connections.

It also manages MAC addressing and the transfer of frames between devices on the same local network.

### Practical Example

When a computer sends data to another device on the same local network, the data is placed into an Ethernet frame containing the source and destination MAC addresses.


These filters help identify Ethernet frames, ARP traffic, and wireless network packets.

---

## 2️⃣ Internet Layer

### Overview

The **Internet Layer** is responsible for logical addressing and routing packets between different networks. It determines how data travels from the source device to its destination using IP addresses.

### Practical Example

When a computer accesses a website hosted on another network, the Internet Layer uses the destination IP address to help route packets toward the correct destination.

---

## 3️⃣ Transport Layer

### Overview

The **Transport Layer** provides communication between applications running on different devices. It manages data delivery using port numbers and transport protocols.

The two main transport protocols are TCP and UDP.

### Common Protocols

**TCP (Transmission Control Protocol)**
- Connection-oriented.
- Provides reliable data delivery.
- Uses acknowledgments and retransmissions.
- Maintains the correct order of data.

**UDP (User Datagram Protocol)**
- Connectionless.
- Does not guarantee delivery or ordering.
- Has lower protocol overhead.
- Commonly used for DNS queries, streaming, and real-time communication.

### Practical Example

When accessing a website through HTTPS, TCP traditionally establishes a connection with the web server before application data is exchanged. QUIC, used by HTTP/3, instead operates over UDP.

---

## 4️⃣ Application Layer

### Overview

The **Application Layer** provides network services that applications use to communicate over a network. It allows users to access websites, transfer files, send emails, and resolve domain names.

### Common Protocols
- HTTP / HTTPS – Web communication.
- DNS – Translates domain names into IP addresses.
- FTP – Transfers files between devices.
- SMTP – Sends email messages.
- DHCP – Automatically assigns IP configuration to devices.
- SSH – Provides secure remote access.

### Practical Example

When a user enters `www.google.com` into a web browser, DNS helps resolve the domain name into an IP address. The browser then communicates with the web server using HTTP or HTTPS.

---

## 🔄 How the TCP/IP Model Works

When a user sends data over a network, the data passes through the four layers. Each layer adds information needed for communication. This process is called **encapsulation**.

When the receiving device gets the data, the layers process it in reverse order. This is called **decapsulation**.

### Encapsulation Process

1. **Application Layer:** Creates the data to be transmitted.
2. **Transport Layer:** Adds TCP or UDP information, including port numbers.
3. **Internet Layer:** Adds IP addressing information.
4. **Network Access Layer:** Encapsulates the packet into a frame for transmission over the network.

### Data Units (PDU)

| TCP/IP Layer | Protocol Data Unit (PDU) |
|---|---|
| Application | Data |
| Transport | Segment (TCP) / Datagram (UDP) |
| Internet | Packet |
| Network Access | Frame |


## 📚 Conclusion

Understanding the TCP/IP Model is essential in networking and cybersecurity because it explains how devices communicate across local networks and the internet. By learning the responsibilities of each layer and identifying their protocols, network analysts can better understand packet transmissions, troubleshoot network issues, and investigate potential security threats.

**Topic:** Networking Fundamentals  
**Model:** TCP/IP – 4-Layer Model
