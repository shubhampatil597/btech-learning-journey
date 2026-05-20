# Day 20 – Linux Services, Daemons & systemctl

# Linux Services

Services are background programs running continuously.

Examples:
- web server
- SSH server
- database server

---

# Daemons

Daemons are Linux background services.

Examples:
- sshd
- systemd
- httpd

---

# systemd

Modern Linux systems use systemd for:
- startup management
- service management

---

# systemctl

systemctl controls services managed by systemd.

---

# Common Commands

Start service:
systemctl start service-name

Stop service:
systemctl stop service-name

Restart service:
systemctl restart service-name

Check status:
systemctl status service-name

Enable at boot:
systemctl enable service-name

Disable startup:
systemctl disable service-name

---

# View Services

systemctl list-units --type=service

---

# Process vs Service

Process:
- any running program

Service:
- managed background process

---

# Key Learnings

- Linux servers depend on services
- daemons run in background
- systemd manages startup/services
- systemctl controls services