# Day 24 – Linux Boot Process & Kernel

# Boot Process

Boot process is sequence of steps after power ON.

Workflow:

Power ON
↓
BIOS/UEFI
↓
Bootloader
↓
Kernel
↓
systemd/init
↓
Services start
↓
Login available

---

# BIOS & UEFI

Firmware systems that initialize hardware.

Responsibilities:
- hardware checks
- initialize RAM/CPU/storage
- start bootloader

---

# Bootloader

Loads operating system.

Common Linux bootloader:
GRUB

---

# Kernel

Kernel is core of operating system.

Responsibilities:
- process management
- memory management
- hardware communication
- storage management

Applications communicate with hardware through kernel.

---

# systemd

Modern Linux startup manager.

Responsibilities:
- start services
- initialize system
- manage startup

---

# uname Command

View kernel information:

uname -a

---

# dmesg

View kernel messages:

dmesg

---

# uptime

Check uptime:

uptime

---

# Key Learnings

- Linux startup follows boot sequence
- GRUB loads kernel
- kernel manages hardware/resources
- systemd starts services