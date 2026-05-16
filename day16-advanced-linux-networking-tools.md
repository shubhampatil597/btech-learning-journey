# Day 16 – Advanced Linux Networking Tools & Local System Networking

# Linux Networking Architecture

Linux networking works using:

Application → Port → Interface → IP → Network

---

# Network Interfaces

Network interfaces connect Linux system to network.

Examples:
- wlan0
- eth0
- lo

Check interfaces:
ip addr

or

ifconfig

---

# Loopback Interface

Loopback interface:
lo

Used for internal communication inside same machine.

Loopback IP:
127.0.0.1

---

# localhost

localhost means current machine itself.

Example:
http://localhost:3000

Used for:
- local testing
- databases
- APIs
- web servers

---

# Ports

Ports are communication channels for applications.

Examples:
- 80 → HTTP
- 443 → HTTPS
- 22 → SSH
- 3306 → MySQL

---

# curl Command

curl is communication & API tool.

Example:
curl https://example.com

View headers:
curl -I https://example.com

Download file:
curl -O file-url

---

# wget Command

wget is downloading utility.

Download:
wget file-url

Resume:
wget -c file-url

Recursive download:
wget -r website-url

---

# curl vs wget

curl:
- APIs
- communication
- server requests

wget:
- downloads
- recursive retrieval
- file saving

---

# Networking Workflow

DNS → IP → Interface → Communication

---

# Key Learnings

- interfaces manage networking
- localhost means current machine
- loopback handles internal communication
- curl communicates with servers
- wget downloads files
- ports separate applications