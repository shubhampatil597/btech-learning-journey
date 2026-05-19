# Day 19 – Linux Users, Groups & sudo

# Linux Users

Linux is multi-user operating system.

Types:
- root user
- normal users
- system users

---

# Root User

Root is administrator user.

Can:
- manage system
- install software
- manage users

UID of root:
0

---

# Current User

Check current user:
whoami

---

# sudo

sudo = SuperUser DO

Allows temporary administrative access.

Example:
sudo apt update

---

# User Information

Stored in:
/etc/passwd

View:
cat /etc/passwd

---

# Groups

Groups are collections of users.

Used for:
- shared access
- permission management

Check groups:
groups

---

# Add User

sudo useradd username

---

# Set Password

sudo passwd username

---

# Delete User

sudo userdel username

---

# Create Group

sudo groupadd developers

---

# Add User to Group

sudo usermod -aG developers username

---

# Home Directory

Each user usually has:
/home/username

---

# Key Learnings

- Linux supports multiple users
- root has full control
- sudo gives temporary admin access
- groups simplify management
- users improve security