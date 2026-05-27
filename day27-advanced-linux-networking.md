# Day 27 – Advanced Linux Networking Internals

# Linux Networking Stack

Applications
↓
TCP/UDP
↓
IP Layer
↓
Network Interface
↓
Physical Network

Linux kernel manages networking internally.

---

# TCP

Reliable communication protocol.

Features:
- acknowledgments
- retransmission
- packet ordering

TCP handshake:
SYN
SYN-ACK
ACK

---

# UDP

Fast connectionless protocol.

Used in:
- streaming
- gaming
- live communication

---

# Sockets

Communication endpoints between processes.

Used in browser-server communication.

---

# NAT

Network Address Translation.

Allows multiple devices to share one public IP.

---

# ARP

Maps:
IP address → MAC address

Used in local network communication.

---

# DNS Hierarchy

Browser cache
↓
OS cache
↓
ISP DNS
↓
Root DNS
↓
TLD DNS
↓
Authoritative DNS

---

# Routing Table

Linux routing tables decide packet paths.

Command:
ip route

---

# localhost

localhost = 127.0.0.1

Represents own system.

---

# Key Learnings

- Linux kernel manages networking
- TCP provides reliable communication
- DNS uses hierarchical architecture
- routing tables control packet direction
- NAT enables shared public IP usage