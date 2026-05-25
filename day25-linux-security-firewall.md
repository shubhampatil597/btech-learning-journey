# Day 25 – Linux Security & Firewall Basics

# Linux Security

Linux security protects:
- servers
- data
- users
- services

---

# Security Layers

- users/groups
- permissions
- passwords
- firewall
- updates

---

# Principle of Least Privilege

Users should only get required permissions.

Improves security.

---

# sudo

Provides temporary administrative access.

Safer than using root continuously.

---

# Firewall

Firewall controls network traffic.

Allows or blocks connections.

---

# Ports

Services use ports for communication.

Examples:
22 → SSH
80 → HTTP
443 → HTTPS

---

# UFW Firewall

Ubuntu commonly uses:
UFW

Check status:
sudo ufw status

Enable firewall:
sudo ufw enable

Allow SSH:
sudo ufw allow 22

---

# Firewall Workflow

Incoming traffic
↓
Firewall checks rules
↓
Allow or block

---

# SSH Security

Security improved using:
- SSH keys
- strong passwords
- restricted root access

---

# Key Learnings

- Linux security is critical
- firewalls protect network access
- ports expose services
- least privilege improves security