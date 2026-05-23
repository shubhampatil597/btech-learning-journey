# Day 23 – SSH, Remote Access & Secure Communication

# Remote Access

Remote access means controlling another computer/server remotely.

---

# SSH

SSH = Secure Shell

Used for:
- secure remote login
- encrypted communication
- server management

---

# SSH Syntax

ssh username@ip-address

Example:
ssh ubuntu@192.168.1.10

---

# SSH Workflow

Client
↓
Internet
↓
Remote server
↓
Encrypted connection established

---

# Authentication Methods

- password authentication
- SSH key authentication

---

# SSH Keys

Two keys:
- public key
- private key

Public key shared with server.
Private key kept secret.

---

# Generate SSH Key

ssh-keygen

Keys usually stored in:
~/.ssh

---

# known_hosts

Stores trusted remote servers.

File:
~/.ssh/known_hosts

---

# SSH Port

Default SSH port:
22

---

# SCP

Used for secure file transfer.

Example:
scp file.txt user@server:/path

---

# Key Learnings

- SSH enables secure remote access
- SSH uses encryption
- SSH keys improve security
- cloud servers are managed remotely