# Data Communications & Networking Projects
## Analyzing Network Protocols with Wireshark

This repository contains two projects from my **Data Communications & Networking (DCN)** course, where I explored **UDP, TCP, and HTTP packet analysis using Wireshark**. These are not just simple lab assignments—each project involved a **deep dive into packet structures, protocol behaviors, and real-world networking insights**.

---

### **Project 1: Tracing UDP Packets and IP Header Analysis**
In this project, I used **Wireshark** to trace UDP packets sent through the `traceroute` command and examined key fields in the **IPv4 header**. The analysis covered:
- **Time-to-Live (TTL), fragmentation, and checksum behaviors**
- **Identification of constant vs. changing fields in IP datagrams**
- **How IP fragmentation occurs when a packet exceeds MTU**
- **Pattern recognition in Identification fields of fragmented packets**

Understanding these low-level behaviors gave me a practical look into how **datagrams traverse a network, how routers process them, and the internal mechanics of packet fragmentation**.

---

### **Project 2: TCP and HTTP Analysis with Wireshark**
This project involved **analyzing TCP segments in HTTP communication**, specifically the transfer of a file (`alice.txt`) using TCP. The project focused on:
- **Tracking TCP handshake (SYN, SYN-ACK, ACK)**
- **Examining sequence numbers and acknowledgments in real data transfers**
- **Calculating Round Trip Time (RTT) for TCP segments**
- **Studying TCP congestion control mechanisms and detecting slow start**
- **Computing network throughput from raw packet data**

Using **Wireshark’s Time-Sequence Graph**, I visualized how TCP congestion control adapts dynamically based on network conditions.

---

## **Why This Matters**
These projects provided **real-world insights into network communication, congestion control, and protocol efficiency**. By analyzing raw packets instead of just theoretical concepts, I developed a **strong understanding of TCP/IP mechanics**, which is essential for networking, cybersecurity, and system performance optimization.

---
### **Technologies Used**
- **Wireshark** for packet capture and deep packet inspection
- **Traceroute** for analyzing network hops and IP fragmentation
- **TCP Sequence Analysis** for congestion control insights
- **Round Trip Time (RTT) calculation** for measuring network performance


---

## **Author**
- **Indhuja Gudluru**  



