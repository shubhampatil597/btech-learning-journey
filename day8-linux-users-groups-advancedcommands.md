# Day 8 – Linux Users, Groups, Ownership & Advanced Commands

## 1. Multi-User Linux System

Linux is a multi-user operating system where multiple users can use the same system securely.

---

## 2. Types of Users

### Root User
Super administrator with full access.

### Normal User
Regular user with limited permissions.

### System Users
Users created for background services.

Examples:
- nginx
- mysql

---

## 3. Groups

Groups are collections of users used for permission management.

Example:
developers

---

## 4. Ownership

Every file/folder has:
- owner
- group

Ownership controls access and permissions.

---

## 5. Important Commands

### whoami
Shows current logged-in user.

### id
Shows user ID and group ID.

### groups
Displays groups of current user.

### chown
Changes ownership.

### chgrp
Changes group ownership.

---

## 6. cat Command

cat is used to display file contents.

Example:
cat notes.txt

Uses:
- reading files
- checking logs
- viewing scripts

---

## 7. cp Command

cp copies files.

Example:
cp file1.txt backup.txt

---

## 8. mv Command

mv moves or renames files.

Example:
mv old.txt new.txt

---

## 9. find Command

find searches files.

Example:
find . -name notes.txt

---

## 10. Key Learnings

- Linux uses users and groups for security
- Ownership controls files
- cat displays files
- cp copies files
- mv moves/renames files
- find searches files