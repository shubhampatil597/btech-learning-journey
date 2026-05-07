# Day 7 – Linux File System & Permissions

## 1. Linux File System

Linux stores everything inside a hierarchical structure starting from root directory "/".

Everything in Linux is treated as a file.

---

## 2. Important Directories

/ → root directory  

/home → user folders  

/bin → important commands  

/etc → configuration files  

/var → logs and changing data  

/tmp → temporary files  

/root → root user home directory  

---

## 3. Root User

Root user has complete administrative control over Linux system.

---

## 4. Permissions

Linux permissions decide who can:
- read
- write
- execute

Permission symbols:
r → read  
w → write  
x → execute  

---

## 5. User Categories

u → owner  
g → group  
o → others  

---

## 6. Permission Example

-rwxr-xr--

Owner:
rwx

Group:
r-x

Others:
r--

---

## 7. chmod Command

Used to change permissions.

Examples:

chmod +x script.sh

chmod -w file.txt

---

## 8. whoami

Displays current logged-in user.

---

## 9. Key Learnings

- Linux uses permission-based security
- Root directory is base of system
- Permissions protect files
- chmod modifies permissions