# Day 9 – Linux Processes & System Monitoring

## 1. Process

A process is a running instance of a program.

Examples:
- browser
- terminal
- editor

Programs become processes when executed.

---

## 2. Process ID (PID)

Every process gets unique ID called PID.

Linux uses PID to manage processes.

---

## 3. Process Lifecycle

Basic stages:
- start
- running
- waiting
- terminated

---

## 4. Foreground vs Background Processes

Foreground:
- runs directly in terminal

Background:
- runs behind the scenes

Cloud servers use many background processes.

---

## 5. Important Commands

### ps
Displays running processes.

Example:
ps aux

---

### top
Shows live system monitoring:
- CPU
- RAM
- processes

---

### kill
Stops process using PID.

Example:
kill 1234

---

### killall
Stops process using process name.

Example:
killall firefox

---

### free -h
Displays RAM usage.

---

### uptime
Displays system uptime and load.

---

## 6. Scheduling

Linux allocates CPU time between multiple processes using scheduling.

---

## 7. Key Learnings

- Programs become processes
- Linux manages processes using PID
- top monitors system live
- kill stops processes
- Linux scheduling enables multitasking