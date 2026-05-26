# Day 26 – Linux Package Ecosystem & Software Management

# Package

Package is installable software bundle.

Contains:
- program files
- libraries
- configuration files

Examples:
- git
- vim
- nginx

---

# Package Manager

Tool used to manage packages.

Examples:
- apt
- dnf
- pacman

---

# Repository

Repository is online software storage.

Linux downloads packages from repositories.

---

# Dependencies

Dependencies are additional software required by another software.

Package managers handle dependencies automatically.

---

# apt Commands

Update package database:
sudo apt update

Upgrade installed software:
sudo apt upgrade

Install software:
sudo apt install package-name

Remove software:
sudo apt remove package-name

Search packages:
apt search nginx

Package info:
apt show git

---

# Termux Package Manager

Update:
pkg update

Install package:
pkg install git

---

# Key Learnings

- packages contain software
- repositories store packages
- package managers install/update software
- dependencies required by software
- updates improve security and stability