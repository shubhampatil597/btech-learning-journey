# Day 21 – Linux Storage, Disk Management & File Systems

# Storage

Storage is used for permanent data saving.

Examples:
- files
- applications
- operating system data

---

# Disk

Disk is physical storage device.

Examples:
- HDD
- SSD
- NVMe SSD

---

# File System

File system organizes and stores files.

Common Linux file systems:
- ext4
- xfs
- btrfs

---

# Partition

Partition is logical division of disk.

Used for:
- organization
- backup
- system separation

---

# Mounting

Mounting connects storage to Linux directories.

Example:
/media

---

# df Command

Check overall disk space:

df -h

---

# du Command

Check file/folder usage:

du -h

Specific folder:
du -sh folder-name

---

# lsblk

View disks and partitions:

lsblk

---

# Key Learnings

- Linux uses file systems to manage storage
- partitions divide disks
- mounting connects storage
- df checks filesystem usage
- du checks folder usage